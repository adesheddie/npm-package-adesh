@adesh_rudra/test
https://img.shields.io/github/issues/adesheddie/npm-package-test.svg
https://img.shields.io/github/forks/adesheddie/npm-package-test.svg
https://img.shields.io/github/stars/adesheddie/npm-package-test.svg
Removes all spaces from a string.

Install
$ npm install @adesh_rudra/test
Usage
const tiny = require("@adesh_rudra/test");

test("So much space!");
//=> "Somuchspace!"

test(2323);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
