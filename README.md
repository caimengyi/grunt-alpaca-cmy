# grunt-alpaca

> alpaca is so cute

## Getting Started
This plugin requires Grunt.

If you haven't used [Grunt](http://gruntjs.com/) before, be sure to check out the [Getting Started](http://gruntjs.com/getting-started) guide, as it explains how to create a [Gruntfile](http://gruntjs.com/sample-gruntfile) as well as install and use Grunt plugins. Once you're familiar with that process, you may install this plugin with this command:

```shell
npm install grunt-alpaca --save-dev
```

Once the plugin has been installed, it may be enabled inside your Gruntfile with this line of JavaScript:

```js
grunt.loadNpmTasks('grunt-alpaca');
```

## The "alpaca" task

### Overview
In your project's Gruntfile, add a section named `alpaca` to the data object passed into `grunt.initConfig()`.

```js
grunt.initConfig({
  alpaca: {
    options: {
      // Task-specific options go here.
    },
    your_target: {
      // Target-specific file lists and/or options go here.
    },
  },
})
```

### Options

#### options.separator
Type: `String`
Default value: `alpaca`

指明是佛祖还是神兽来保佑我们的代码

A string value that is used to do something with whatever.

#### options.punctuation
Type: `String`
Default value: `//`

文件中拼接佛祖或者神兽时使用的注释符

A string value that is used to do something else with whatever else.

### Usage Examples

#### Default Options


```js
grunt.initConfig({
  alpaca: {
    options: {
      'who': 'alpaca',
      'commentSymbol': '//'
      },
    dist: ['example/*.js']
  },
})
```


## Contributing
In lieu of a formal styleguide, take care to maintain the existing coding style. Add unit tests for any new or changed functionality. Lint and test your code using [Grunt](http://gruntjs.com/).

## Release History
2018.6.13&nbsp;&nbsp;&nbsp;v0.0.1&nbsp;&nbsp;&nbsp; init

## License
Copyright (c) 2018 caimengyi. Licensed under the MIT license.
