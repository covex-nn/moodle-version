# Version

**Version** is a library that helps us with managing the <code>moodle-source</code> package version.

<a href="https://travis-ci.org/covex-nn/moodle-version/" target="_blank"><img src="https://travis-ci.org/covex-nn/moodle-version.png?branch=master" /></a>

## Installation

* Use this template for composer.json to download Moodle 2.8

```json
{
  "require-dev" : {
    "covex-nn/moodle-version" : "~2.8"
  }, 
  "extra" : {
    "branch-alias": {
      "dev-master": "1.0.x-dev"
    }
  }, 
  "config" : {
    "bin-dir" : "bin"
  }, 
  "minimum-stability" : "dev", 
  "prefer-stable" : true
}
```

* Run <code>cd www/admin/cli && php install.php</code> to install Moodle
* See [moodle-package](https://github.com/covex-nn/moodle-package) for details
