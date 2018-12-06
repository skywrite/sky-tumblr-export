Node.js - sky-tumblr-export
================

Export your Tumblr blog to Markdown.


Why?
----

I'm tired of using Tumblr. Well, actually I haven't used Tumblr since 2011. But I wanted the blog posts in Markdown so that I could use a static blog generator. I ultimately wrote my own static blog generator, [sky][sky]. But you can use this to dump your Tumblr blog and use any Markdown static blog generator that you like.


Requirements
------------

You must have [pandoc](http://johnmacfarlane.net/pandoc/) installed. Get it here: http://code.google.com/p/pandoc/downloads/list


Installation
------------

You'll need to install Node.js. You can get it here: http://nodejs.org/download/

    npm install -g sky-tumblr-export


CLI
---

    
    Usage: sky-tumblr-export [options]

    Options:

    -h, --help          output usage information
    -V, --version       output the version number
    -u, --url [url]     REQUIRED. The url of the Tumblr blog.
    -d, --dir <dir>     The directory to dump the files. Default is the current directory.
    -t, --titles        Output titles in markdown.
    -g, --generator     Further optimize output for static site generator. Only `hugo` for now.
    --download-images   Downloads all images and sets relative paths in content
    --debug             Set to debug mode.
    --api-key <apikey>  The API key. Optional.



Example
------

    sky-tumblr-export -u techneur.com -d /tmp/techneur --titles

### Results: ###

    ├── 2010
    │   ├── 02
    │   │   ├── entrepreneurial-heroes.md
    │   │   ├── inspiration-perishable.md
    │   │   └── meeting-deadlines.md
    │   ├── 03
    │   │   ├── 2-apps-are-better-than-1.md
    │   │   ├── iphone-company-struggle-1.md
    │   │   ├── iphone-company-struggle-2.md
    │   │   ├── its-all-our-fault-why-building-a-business-on-the.md
    │   │   └── social-media-not-about-you.md
    ├── 2011
    │   ├── 01
    │   │   ├── 500-revenue-growth-in-2010.md
    │   │   ├── become-master-of-metaphors.md
    │   │   ├── eric-schmidt-and-the-google-triumvirate.md
    └── sky
        └── config.json

(truncated for brevity)

Contributors
------------

* [JP Richardson](http://github.com/jprichardson)
* [Adam Brault](http://github.com/adambrault)


License
-------

(MIT License)

Copyright 2013, JP Richardson  <jprichardson@gmail.com>


[sky]: https://github.com/skywrite
