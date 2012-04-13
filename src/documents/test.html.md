---
title: Test page with markdown
layout: default
---

Yeah! With codeblock?

``` html
<html>
    <head>
        <meta charset="utf-8" />
        <title>QUnit Tests</title>
        <link rel="stylesheet" href="qunit.css">
    </head>
    <body>
        <h1 id="qunit-header">QUnit Hello World</h1>
        <h2 id="qunit-banner"></h2>
        <ol id="qunit-tests"></ol>
        <script src="qunit.js"></script>
        <script>
            test("hello", function() {
                ok(true, "world");
            });
        </script>
    </body>
</html>
```