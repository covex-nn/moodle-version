# Version

**Version** is a library that helps with managing the <code>moodle-source</code> package version.

## Installation

* Use this template for composer.json to install moodle

```json
{
  "require-dev" : {
    "covex-nn/moodle-version" : ">=1.0.0"
  }, 
  "repositories" : [
    { "type" : "composer", "url" : "https://raw.github.com/covex-nn/moodle-version/master" }
  ], 
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
