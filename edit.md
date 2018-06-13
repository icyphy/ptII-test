---
layout: default
---
# How to edit the pages in https://icyphy.github.io/ptII-test/

The static pages like this one are edited via the `gh-pages` branch of the [Github ptII-test repo](https://github.com/icyphy/ptII-test)

```
      git clone --depth=1 --single-branch --branch=gh-pages https://github.com/icyphy/ptII-test gh-pages 
```

Note that we use the ptII-test repo here instead of the ptII repo so as to avoid cluttering the ptII changelog with lots of commits from the tests.

See [https://pages.github.com/](https://pages.github.com/) for details.
    
The pages in the [downloads](downloads/index.html) directory are created as part ofthe [Travis-ci ptII build](https://travis-ci/icyphy/ptII), which runs [$PTII/bin/ptIITravisBuild.sh](https://github.com/icyphy/ptII/blob/master/bin/ptIITravisBuild.sh)


Note
---
* [Back up to the top](index.html)
