2TE-Bootstrap
=============

This is example of how to build a golang webserver with another layer of template engine in Python for amazing performance at server and client side!!!

    This repo should better be treated as a starter-boilerplate more then example

This is example for complete Bootstrap skeleton website using Cheeath OR Jinja2 template engine as the First Template engine layer and Goland as the webserver/second template engine layer.

### Read more about the idea of this example and what I call first-layer/second-layer template engine
* Read [this post](http://itekblog.com/template-engine-need-two/): Why I use Two Templates Engine in one web application.
* Based on [2TE repo](https://github.com/ET-CS/2TE). Read more at 2TE repo about the 2-Template-Engine example project.

### What different from 2TE
* I've made it more complex and arranged the folders and files as I like (and not pure simple).
* Added few bash script files for fast compiling of the app and watch (reload code)
* I've made this example with Cheetah & Jinja2 templates engine as well. read more at templates/render.sh. .tmpl files are for cheetah, .html files are for jinja2.
* I've disabled cache in the golang side with comment on how to activate it again.

### Deploy
Deploy is fun: 2 files only! 'main' and 'index.min.html'. buildndeploy.sh could be easily built to build and deploy to your server. Personaly, I am running golang servers using Supervisor but there are lot of other options.