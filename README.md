# Computer Graphics Club Website
The Computer Graphics Club is a student organization at San José State University, in San Jose, CA. Formed out of a need to represent students with an interest in computer graphics, the CG Club aims to be an asset to student life by connecting the SJSU community to the CG industry.

See the site live at [sjsucg.org](http://sjsucg.org).

## Installation & Usage
    bundle install
    jekyll serve --watch

_Note: Requires Ruby version 1.9.3 =>. For example use [rbenv](https://github.com/sstephenson/rbenv)_   

Run rake task. **NOTE: It will deploy the generated site to _gh-pages_ branch overwriting it**    
```
rake site:publish
```

## Authors

Jekyll theme originally built by [sendtoinc.com](https://sendtoinc.com), modified by [Justin Tennant](http://justintennant.me), Karl Lapuz, and Shelley Wu.

## Todo:

+ Fix mobile version
+ Add blog category for `news`, update index to show `news` posts instead of static content
