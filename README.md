# generator-gulp-underscores [![Build Status](https://travis-ci.org/webmakersteve/generator-gulp-underscores.svg?branch=master)](https://travis-ci.org/webmakersteve/generator-gulp-underscores)

> [Yeoman](http://yeoman.io) generator


## Getting Started

### What is Yeoman?

Trick question. It's not a thing. It's this guy:

![](http://i.imgur.com/JHaAlBJ.png)

Basically, he wears a top hat, lives in your computer, and waits for you to tell him what kind of application you wish to create.

Not every new computer comes with a Yeoman pre-installed. He lives in the [npm](https://npmjs.org) package repository. You only have to ask for him once, then he packs up and moves into your hard drive. *Make sure you clean up, he likes new and shiny things.*

```bash
npm install -g yo
```

### Yeoman Generators

Yeoman travels light. He didn't pack any generators when he moved in. You can think of a generator like a plug-in. You get to choose what type of application you wish to create, such as a Backbone application or even a Chrome extension.

To install generator-gulp-underscores from npm, run:

```bash
npm install -g generator-gulp-underscores
```

Finally, initiate the generator:

```bash
yo gulp-underscores
```

### Options

**Theme Author**
This should be the theme author as it will be listed in the stylesheet. Defaults to the folder name with the suffix author. Don't leave it like that :)

**Theme Name**
Awesome theme name. Defaults to the folder name.

**Theme Slug**
The prefix for all of your theme's functions. Defaults to the folder name

**Theme URI**
Theme URI listed in the stylesheet.

**Theme Description**
Description that will appear on your theme's page

**Bootstrap?**
Choose whether to include bootstrap. Defaults to yes.

**SASS?**
Choose whether to include SASS. Defaults to yes

**Server Address**
The address your local server runs on. Required so browsersync can do its thing.

### Getting To Know Yeoman

Yeoman has a heart of gold. He's a person with feelings and opinions, but he's very easy to work with. If you think he's too opinionated, he can be easily convinced.

If you'd like to get to know Yeoman better and meet some of his friends, [Grunt](http://gruntjs.com) and [Bower](http://bower.io), check out the complete [Getting Started Guide](https://github.com/yeoman/yeoman/wiki/Getting-Started).

### Options

Currently the only options that work are the ones that have to do with the templating. This is mainly for projects that I scaffold, and they (almost) always contain bootstrap and *always* use SASS.

If there is demand in this at all I will add more :)

## License

MIT
