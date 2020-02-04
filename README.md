# Problemas-com-Ruby-on-rails

* Ruby version: 2.7.0p0 (2019-12-25 revision 647ee6f091) [x86_64-linux]
* Rails version: Rails 6.0.2.1


Começando, criei uma pasta no Desktop chamada ExampleFolder, abri no terminal e digitei o seguinte comando:
‘rails new example’
Para criar um diretório com o nome de ‘example’.


Primeiro erro: 
![Screenshot from 2020-02-04 11-00-43](https://user-images.githubusercontent.com/60013328/73752911-869aea80-4740-11ea-8b98-83bd0a7333d6.png)

Digitei o que foi sugerido ‘bundle lock –add-platform x86-mingw32 x86mswin32 x64ming32 java’
Ele retornou:
            
'Fetching gem metadata from https://rubygems.org/............
 Fetching gem metadata from https://rubygems.org/.
 Resolving dependencies...
 Writing lockfile to /home/ftb_oy/Desktop/ExampleFolder/example/Gemfile.lock’

Pelo visto sem nenhum problema.

Próximo erro:

![Screenshot from 2020-02-04 11-02-32](https://user-images.githubusercontent.com/60013328/73753143-f14c2600-4740-11ea-99e4-b89f26cc71ad.png)

O primeiro parágrafo em amarelo é o mesmo erro que o primeiro, então já foi resolvido. Depois diz que a versão do Bundler é antiga. Eu digito o que sugeriu: ‘gem install bundler:2.1.4’
E retorna:

Successfully installed bundler-2.1.4
Parsing documentation for bundler-2.1.4
Done installing documentation for bundler after 1 seconds
ERROR:  Could not find a valid gem '2.1.4' (>= 0) in any repository
1 gem installed

Pesquisei no StackOverflow e tentei ‘gem install bundler https://rubygems.org/gems/bundler/versions/2.1.4’ mas deu o mesmo ‘could not find a valid gem [...]’
