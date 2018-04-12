## Multiple ranges in one line

This folder is a reproduction of an issue reported in Desktop: https://github.com/desktop/desktop/issues/2700

Here's a screenshot of the issue:

![](https://user-images.githubusercontent.com/359239/29397119-850b247a-835f-11e7-94f5-55ca7fe319b9.png)

The steps to reproduce this are as follows:

 - first commit - [2c03970](https://github.com/desktop/diff-tests/commit/2c0397080276eafd205672560998707a1ce72a75) - adding the baseline file contents
 - second commit - [2c22303](https://github.com/desktop/diff-tests/commit/2c2230362afd3e73ef44569e17251edd74c8f2bc) - apply changes to demonstrate the issue

Unified diff on website of the second commit:

<img width="1011" rc="https://user-images.githubusercontent.com/359239/38650668-7b12588e-3e40-11e8-8325-62ab27a16dd8.png">

Note the first line of the diff highlights the ranges of characters that have been updated.