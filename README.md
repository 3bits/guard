Guard 3bits
=====

##Guard:
*gem install guard

##Necessário:
*guard-sass
*guard-compass
*guard-process
*guard-concat 0.0.4 
 *git clone git://github.com/makevoid/guard-concat
  cd guard-concat
  gem build guard-concat.gemspec 
  gem install guard-concat-0.0.4.gem
*gem install juicer
  *$ juicer install yui_compressor
  $ juicer install closure_compiler
  $ juicer install jslint

##Opcional:
*guard-livereload
*guard-shell
