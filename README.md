efilnepo-less
=============

This library contains custom less files for common tasks and collection of fonts.

## Installation

```
bower install efilnepo-less  
```

or include it to your bower.json to dependency area.

```
"dependencies": {
	"efilnepo-less": "~1.0.1"
}
```

## Folder structure

```
less
  -- font-*.less // include @font-face for * font
  -- helpers.less // examples which help to remember use cases for specific properties
  -- margins.less // generate margin-top classes from negative mt-120 to positive mt120 (120 - pixels)
  -- mixins.less // custom mixins
  -- variables.less // variables
  -- efilnepo.less // combine all files together
fonts
  -- * fonts
```

