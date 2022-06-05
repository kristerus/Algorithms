[[Additional Algorithms]]

### Symetric difference algorithm

An algorithm which aims to find the values unique in two given arrays.

const differentiatior = (arr1, arr2) => [
 ...arr1.filter((i) => !arr2.includes(i)),
 ...arr2.filter((i) => !arr1.includes(i)),];
const symDiff = (...args) => [...newSet(args.reduce(differentiatior))];
symDiff([1, 2, 3], [5, 2, 1, 4]);


#algorithms 