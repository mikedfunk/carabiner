Carabiner
=====================
*All credit to [Tony Dewan](http://codeigniter.com/forums/member/83507/) for original library.*

This is Carabiner implemented as a codeigniter third_party module. Just clone into third_party/carabiner and go!

[Documentation](http://codeigniter.com/wiki/Carabiner/)

---------------------

This adds Less CSS PHP compiling to the mix. Just pass .less files via ```$this->carabiner->css('file.less')``` and away we go! It puts the compiled css file into the configured cache folder before minifying and combining.

This repo contains the leafo.net LessPHP compiler as a submodule, so be sure to ```git submodule update --init``` after cloning.