## js-heap-tests [![NPM version](https://img.shields.io/npm/v/@tyriar/heap-tests.svg?style=flat)](https://www.npmjs.org/package/@tyriar/heap-tests)

[![Build Status](http://img.shields.io/travis/Tyriar/js-heap-tests.svg?style=flat)](http://travis-ci.org/Tyriar/js-heap-tests)

A set of JavaScript heap data structure tests.

### Install

```bash
npm install --save-dev @tyriar/heap-tests
```

### Usage

```js
import Heap from '../';
import test from 'ava';
import testHelper from '@tyriar/heap-tests/insert-tests';

testHelper.run(test, Heap);
```

### See also

- [js-data-structures](https://github.com/Tyriar/js-data-structures)
- [js-binary-heap](https://github.com/Tyriar/js-binary-heap)
- [js-binomial-heap](https://github.com/Tyriar/js-binomial-heap)
- [js-fibonacci-heap](https://github.com/Tyriar/js-fibonacci-heap)
