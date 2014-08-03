2TE-Bootstrap
=============

 This repo is better treated as starter-boilerplate then example

Based on 2TE repo, I've made an example for a complete Boostrap skeleton website.
Also, I've made it more complex and arranged the folders and files as I like (and not simple).
Added few script files for fast working.

I've linked the .sh file, so the root .build will also compile templates. compile.sh will also compile js and css

I've made this example with Cheetah & Jinja2 templates engine as well. read more at templates/render.sh. .tmpl files are for cheetah, .html files are for jinja2.

Also, I've disabled cache in the golang side with comment on how to activate it again.

Read more at 2TE repo about 2-Template-Engine example.

Deploy is fun: 2 files only! 'main' and 'index.min.html'. buildndeploy.sh could be easily built to build and deploy to your server. Personaly, I am running golang servers using Supervisor but there are lot of other options.