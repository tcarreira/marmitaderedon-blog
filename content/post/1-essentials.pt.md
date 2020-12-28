+++
title = "Podcast a custo zero (o que é essencial)"
author = "Tiago Carreira"
date = "2020-12-26T12:00:00.000+00:00"
description = "Podcast a custo zero (o que é essencial)"
thumbnail = "images/dog_phonograph_400.jpg"

featured = false
categorias = ["Tutorial"]
+++


**>> Mas afinal o que é um podcast? <<**

Tecnicamente, é apenas uma lista de ficheiros audio, listados num [feed RSS](https://pt.wikipedia.org/wiki/RSS).  
Mas talvez esta seja uma visão demasiado simplificada da tecnologia.

Aqui fica uma breve análise dos pontos importantes a ver num podcast em 3 categorias: essenciais, recomendados e opcionais.

{{% 
figure
src="../../../images/dog_phonograph_400.jpg" 
attr="<small>\"Dog Looking at and Listening to a Phonograph\" por Beverly & Pack está sob lincença CC BY 2.0</small>"
attrlink="https://live.staticflickr.com/3546/3353936487_2599d7b8dc_b.jpg"
%}}

## Essenciais

- Conteúdo

  A coisa mais imprescindível num podcast é o conteúdo - é a alma do podcast e é o que os ouvintes consomem.
  Esse conteúdo deve ser capturado/gravado de forma limpa e sem ruídos externos.

- Captação

  Este é um dos pontos mais importantes na qualidade do podcast. 
  E infelizmente não há atalhos. 
  Para ter um podcast de qualidade é essencial um microfone de qualidade (mas não só!).
  Se o objetivo do podcast é **apenas aprender e experimentar**, há alternativas gratuítas (o que foi feito no podcast [Marmita de Redon](https://marmita.pt)).

- Ficheiros áudio: episódios em formato digital
  
  Esta é a forma de transmitir o conteúdo até aos ouvintes - um ficheiro áudio, normalmente em formato MP3.
  Este ficheiro deve estar alojado num site com acesso público.

  Existem várias formas de alojamento destes ficheiros, umas mais caras ou baratas, mais livres ou proprietárias, etc.
  Temos como exemplo o [archive.org](https://archive.org), [S3 da AWS](https://aws.amazon.com/s3/), 
  Dropbox/Drive/OneCloud, ou mesmo o próprio site do podcast.

- Feed RSS

  Esta parte é fulcral na distribuição do podcast. 
  É aquilo que os diretórios de podcasts (Apple Podcasts, Spotify, etc.) exigem para listar um podcast.

  Trata-se apenas de um ficheiro em formato XML, destinado a ser lido e consumido por computadores, 
  com todas as informações do podcast (título, autores, imagem ...), 
  incluindo a lista de todos os episódios (e a localização dos ficheiros áudio).

  É a partir desta fonte que os ouvintes são notificados da existência de novos episódios (através das aplicações onde consomem o conteúdo).


## Recomendados

- Site oficial

  Apesar de não ser obrigatório, o site é muitas vezes procurado para encontrar algumas informações relativas ao podcast.
  É provavelmente o sítio certo para encontrar o contacto dos autores.

  A alternativa mais fácil a um site dedicado será a utilização das próprias plataformas de podcast, 
  que normalmente providenciam uma "cara" do podcast, com a lista de episódios e as respetivas notas.

- Redes sociais

  Nos dias de hoje, a divulgação é das coisas mais importantes ao sucesso do podcast.
  Ninguém vai procurar um podcast do qual nunca ouviu falar. 

- Marca

  Desde o genérico até às cores e imagem, este é normalmente o primeiro contacto com o podcast.
  Uma imagem coerente e que representa a marca (o podcast) mostra profissionalismo e dedicação. 

- Estatísticas

  Saber quantas vezes os episódios foram ouvidos pode ter ou não alguma consequência,
  mas existe sempre a curiosidade de saber a quantas pessoas chega a nossa voz.


## Opcionais

- Monetização

  Este pode ser um dos objetivos iniciais do podcast (embora eu não recomende). 
  Tirar alguns rendimentos do podcast é possível, desde que haja um número considerável de ouvintes.
  A forma mais comum de monetização é através de anúncios, 
  normalmente negociado com as marcas que pagam para o _podcaster_ falar delas.

- Um plano

  O que fazer depois? 
  Faz sentido continuar o projeto para 3 ouvintes mensais?
  A partir de quantos ouvintes eu quero profissionalizar o podcast?
  Quero subcontratar serviços agora ou quando tiver X ouvintes?  
  Fazer este tipo de planos no início, é útil a meio do caminho, quando as dúvidas surgem.


# Como fazer a custo zero

Bem, foi desta forma que foi feito no podcast [Marmita de Redon](https://marmita.pt)

|      O quê      | Como                                                                                                                                                                                                                                                                                   |
|:---------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    Conteúdo     | Um grupo de 4 amigos decide sobre o que vai ser falado no próximo episódio                                                                                                                                                                                                             |
|    Captação     | De forma a manter a qualidade num mínimo aceitável, gravamos cada episódio com os nossos smartphones. Atrevo-me a dizer que esta é a única coisa que não apresenta profissionalismo sem investimento                                                                                   |
| Ficheiros áudio | Cada episódio é editado com o software livre [Audacity](https://www.audacityteam.org/) e depois é enviado para o [archive.org](https://archive.org)                                                                                                                                    |
|    Feed RSS     | Foi criado novo código aberto para suportar completamente o feed RSS usado em _podcasting_ ([código no Github](https://github.com/Marmita-de-Redon/hugo-redon-podcast/blob/master/layouts/feed/rss.xml))                                                                               |
|  Site oficial   | Site feito em [Hugo - um _framework_ de sites estáticos](https://gohugo.io/) e alojado no [Github Pages](https://pages.github.com/) gratuitamente ([código no Github](https://github.com/Marmita-de-Redon/website))                                                                    |
|  Redes sociais  | Contas gratuitas em Instagram, Facebook, Twitter, Youtube, Github, Disqus                                                                                                                                                                                                              |
|      Marca      | As imagens vetoriais editadas em [Inkscape](https://inkscape.org/), com recurso a materiais do [Flaticon](https://www.flaticon.com/) e disponibilizado livremente em [Github](https://github.com/Marmita-de-Redon/brand). As cores são coerentes entre o site, imagens e redes sociais |
|  Estatísticas   | É possível obter [estatísticas básicas gratuítas](https://create.blubrry.com/resources/podcast-media-download-statistics/basic-statistics/) disponibilizadas pelo serviço Blubrry                                                                                                      |
