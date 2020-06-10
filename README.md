# testcafe-reporter-lm
[![Build Status](https://travis-ci.org/jamesmart77/testcafe-reporter-lm.svg)](https://travis-ci.org/jamesmart77/testcafe-reporter-lm)

This is the **lm** reporter plugin for [TestCafe](http://devexpress.github.io/testcafe).

<p align="center">
    <img src="https://raw.github.com/jamesmart77/testcafe-reporter-lm/master/media/preview.png" alt="preview" />
</p>

## Install

```
npm install testcafe-reporter-lm
```

## Usage

When you run tests from the command line, specify the reporter name by using the `--reporter` option:

```
testcafe chrome 'path/to/test/file.js' --reporter lm
```


When you use API, pass the reporter name to the `reporter()` method:

```js
testCafe
    .createRunner()
    .src('path/to/test/file.js')
    .browsers('chrome')
    .reporter('lm') // <-
    .run();
```

## Author
James Martineau (http://jamesmart77.github.io)
