2TE-Bootstrap
=============

This is example of how to build a golang webserver with another layer of template engine in Python for amazing performance at server and client side!!!

    This repo should better be treated as starter-boilerplate more then example

Based on [2TE repo](https://github.com/ET-CS/2TE), I've made an example for a complete Bootstrap skeleton website using Cheeath OR Jinja2 as the First Template engine layer and Goland as the webserver/second template engine layer.

### What different from 2TE
* I've made it more complex and arranged the folders and files as I like (and not simple).
Added few script files for fast working.
* I've linked the .sh file, so the root .build will also compile templates. compile.sh will also compile js and css
* I've made this example with Cheetah & Jinja2 templates engine as well. read more at templates/render.sh. .tmpl files are for cheetah, .html files are for jinja2.
* I've disabled cache in the golang side with comment on how to activate it again.

Read more at [2TE repo](https://github.com/ET-CS/2TE) about 2-Template-Engine example.
Read [this post](http://itekblog.com/template-engine-need-two/): Why I use Two Templates Engine in one web application.

Deploy is fun: 2 files only! 'main' and 'index.min.html'. buildndeploy.sh could be easily built to build and deploy to your server. Personaly, I am running golang servers using Supervisor but there are lot of other options.