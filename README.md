Arquivos de linguagem do Laravel 5.5 - Português do Brasil

Essa tradução foi atualizada a partir do conteúdo disponibilizado por Leomhl neste link: https://github.com/Leomhl/laravel-5.4-pt-br-localization
Instalação

    Clonar este projeto para uma pasta dentro de resources/lang/

$ cd resources/lang/
$ git clone https://github.com/eduardobelchior/laravel-5.5-pt-br-localization.git ./pt-br

Você pode remover o diretório .git para poder incluir e versionar os arquivos deste projeto no seu repositório.

$ rm -r pt-br/.git/

    Configurar o Framework para utilizar a linguagem como Default

// Linha 80 do arquivo config/app.php
'locale' => 'pt-br',
