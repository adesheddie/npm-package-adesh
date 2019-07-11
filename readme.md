# @adesh_rudra/test



Removes all spaces from a string.

## Install
$ npm install @adesh_rudra/test
## Usage
const test = require("@adesh_rudra/test");

test("So much space!");
//=> "Somuchspace!"

test(2323);
//=> Uncaught TypeError: Tiny wants a string!
//    at tiny (<anonymous>:2:41)
//    at <anonymous>:1:1
