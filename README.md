# Sublime text snippets

## Content
* [HTML](#html)
* [JavaScript](#javascript)
* [Python 3](#python-3)

## HTML

### HTML core
From `html` + `[tab]`
```html
<!DOCTYPE html>
<html lang="en">

    <head>
        <!-- styles -->
        <link rel="stylesheet" href="CSS_FILE_PATH.css">
        <!-- minimal configuration -->
        <link rel="icon" href="ICON_PATH/ICON_URL">
        <meta charset="utf-8">
        <meta name="description" content="DESCRIPTION" />
        <title>${1:title}</title>
        <!-- open graph -->
            <!-- Informations -->
        <meta property="og:description" content="OPEN_GRAPH_DESCRIPTION" />
        <meta property="og:title" content="OPEN_GRAPH_TITLE" />
        <meta property="og:type"  content="website" />
        <meta property="og:url"   content="WEBSITE_URL" />
            <!-- Image -->
        <meta property="og:image" content="URL_TO_IMAGE" />
        <meta property="og:image:alt"    content="Website icon" />
        <meta property="og:image:height" content="80" />
        <meta property="og:image:secure_url" content="URL_TO_IMAGE" />
        <meta property="og:image:type"  content="image/png" />
        <meta property="og:image:width" content="80" />
        <meta property="og:locale" content="en_GB" />
    </head>

    <body>
        <!-- JS file -->
        <script src="JS_FILE_PATH.js"></script>
    </body>
</html>
```



## Javascript

### ajax
From `ajax` + `[tab]`
```javascript
var xhttp = new XMLHttpRequest();
xhttp.onreadystatechange = function() {
    if (this.readyState == 4 && this.status == 200) {
        console.log(this.responseText) ;
    }
};
xhttp.open("GET", "target", true);
xhttp.send();
```

### logger
From `log` + `[tab]`
```javascript
console.log("this");
```

## Vue.js

### template
From `template` + `[tab]`
```html
<template lang="html">

</template>

<script>
export default {
}
</script>

<style lang="css">
</style>
```

## Python 3

### Python 3 core
From `p3` + `[tab]`
```python
# !/usr/bin/env python3
# -*- coding: utf-8 -*-

def main() :
    pass

if __name__ == '__main__':
    main()
```


# Contributions

Feel free to contribute !
