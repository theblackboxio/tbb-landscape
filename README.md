# tbb-landscape

This Polymer component is a landscape image from left to right, easy to extend and integrate.

## Usage 

Include the dependency in your html:

    <link rel="import" href="<your components path>/tbb-landscape/tbb-landscape.html">
    
    ...

    <tbb-landscape imageSrc="<image source>" height="400" blur gray>
        <h1>I'm a landscape!</h1>
        <h2>With a fancy subtitle</h2>
    </tbb-landscape>
    

## Options

* `height` numeric in pixels, the height of the landscape section.

* `imageSrc` string, url or resource path of the background image.

* `blur` implicit boolean (present or not present), if present adds 5% blur filter.

* `gray` implicit boolean (present or not present), if present adds grayscale 100% filter.

## Licenses

Copyright (c) 2015 theblackbox.io Authors. All rights reserved.
This code may only be used under the BSD style license found at LICENSE
The complete set of authors and contributors may be found at http://theblackboxio.github.io/humans.txt

