Guard 3bits
=====

1. Usando o terminal entre na pasta do projeto

    ``cd /theme-do-projeto``

2. Use o [Bundler](http://bundler.io/) para instalar todas as gems:

    ``bundle install``

3. Após instalar todas as gems do projeto rode o guard com o comando:

    ``bundle exec guard``
  
    Você pode definir a sequência de execução do Guard:

     bundle exec guard --group frontend concat linter
