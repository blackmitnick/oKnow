# **Sass**

- [**Sass**](#sass)
  - [What You Should Already Know](#what-you-should-already-know)
  - [So what's Sass?](#so-whats-sass)
  - [Why Use Sass?](#why-use-sass)
  - [How Does Sass Work?](#how-does-sass-work)
  - [Sass File Type](#sass-file-type)
  - [Sass Comments](#sass-comments)
  - [Sass Example](#sass-example)
  - [Sass Installation](#sass-installation)
    - [System Requirements for Sass](#system-requirements-for-sass)
    - [Install Sass](#install-sass)
  - [Official Sass Web Site](#official-sass-web-site)

<h2>Css With Superpowers.</h2>

## What You Should Already Know

Before you continue you should have a basic understanding of the following:

.HTML

.CSS

Am try on my best to elaborate important concept concerning about sass with real examples through code.

## So what's Sass?

>Sass stands for Syntactically Awesome Stylesheet
>Sass is an extension to CSS
>Sass is a CSS pre-processor
>Sass is completely compatible with all versions of CSS
>Sass reduces repetition of CSS and therefore saves time
>Sass was designed by Hampton Catlin and developed by >Natalie Weizenbaum in 2006
>Sass is free to download and use

<p> Sass reduces repetition of CSS and therefore saves time.
</p>

## Why Use Sass?

Stylesheets are getting larger, more complex, and harder to maintain. This is where a CSS pre-processor can help.

Sass lets you use *features* that do not exist in CSS, like variables, nested rules, mixins, imports, inheritance, built-in functions, and other stuff.

## How Does Sass Work?

A browser does not understand Sass code. Therefore, you will need a Sass pre-processor to convert Sass code into standard CSS.

This process is called transpiling. So, you need to give a transpiler (some kind of program) some Sass code and then get some CSS code back.

>***Tips***: Transpiling is a term for taking a source code written in one language and transform/translate it into another language.

## Sass File Type

Sass files has the "```.scss```" file extension.

## Sass Comments

Sass supports standard CSS comments ``` /*comment*/ ```, and in addition it supports inline comments ```// comment```:

## Sass Example

```sass
/* define primary colors */
$your-color_1: #a2b9bc;
$your-color_2: #b2ad7f;

/* use the variables */
.main-header {
  background-color: your-color_1; // here you can put an inline comment
  color: your-color_2;
}
 ```

## Sass Installation

### System Requirements for Sass

.Operating system - Sass is platform independent

.Browser support - Sass works in Edge/IE (from IE 8), Firefox, Chrome, Safari, Opera

. Programming language - Sass is based on Ruby

### Install Sass

There are several ways to install Sass in your system. There are many applications that will get you up and running with Sass in a few minutes for Mac, Windows, and Linux. Some of these are free, but some are paid apps.

> You can read more about them here: sass-lang.com/install

## Official Sass Web Site

Read more about Sass at the official Sass web site: <https://sass-lang.com/>
