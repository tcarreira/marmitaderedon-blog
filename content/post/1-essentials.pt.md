+++
title = "Podcast a custo zero (o que é essencial)"
author = "Tiago Carreira"
date = "2021-02-12T12:00:00.000+00:00"
description = "Podcast a custo zero (o que é essencial)"
thumbnail = "images/dog_phonograph_400.jpg"

featured = false
categorias = ["Tutorial"]
aliases = ["1-essenciais"]
+++


**>> Mas afinal o que é um podcast? <<**

Tecnicamente, é apenas uma lista de ficheiros áudio, listados num [feed RSS](https://pt.wikipedia.org/wiki/RSS).  
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

- Captação

  Este é um dos pontos mais importantes na qualidade do podcast. 
  Infelizmente não há atalhos:
  para ter um podcast de qualidade é essencial um microfone de qualidade (mas não só!).  
  No entanto, se o objetivo do podcast é **aprender e experimentar**, há alternativas gratuitas (o que foi feito no podcast [Marmita de Redon](https://marmita.pt)).

- Ficheiros áudio: episódios em formato digital

  Esta é a forma de transmitir o conteúdo até aos ouvintes - um ficheiro áudio, normalmente em formato MP3.
  Este ficheiro deve estar alojado num site com acesso público.

- Alojamento 

  Existem várias formas de alojamento dos ficheiros áudio, umas mais caras ou baratas, outras mais livres ou proprietárias.
  Temos vários exemplos: 
  [archive.org](https://archive.org),
  [S3 da AWS](https://aws.amazon.com/s3/),
  [Dropbox](https://dropbox.com)/[Drive](https://drive.google.com)/[OneDrive](https://www.microsoft.com/microsoft-365/onedrive/online-cloud-storage),
  ou mesmo o próprio site do podcast.

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

- Periodicidade

  É útil para os ouvintes saberem quando esperar o próximo episódio, 
  dá um aspeto mais "saudável" ao podcast.

- Monetização

  Este pode ser um dos objetivos iniciais do podcast (embora eu não recomende). 
  Tirar alguns rendimentos do podcast é possível, desde que haja um número considerável de ouvintes.
  A forma mais comum de monetização é através de anúncios, 
  normalmente negociados com as marcas que pagam para o _podcaster_ falar delas.

- Um plano

  O que fazer depois? 
  Faz sentido continuar o projeto para 3 ouvintes mensais?
  A partir de quantos ouvintes eu quero profissionalizar o podcast?
  Quero subcontratar serviços agora ou quando tiver X ouvintes?  
  Fazer este tipo de planos no início, é útil a meio do caminho, quando as dúvidas surgem.


# Como fazer a custo zero

Melhor do que explicações, o melhor é ver um caso prático.
Foi desta forma que aconteceu o podcast [Marmita de Redon](https://marmita.pt):

|      O quê      | Como                                                                                                                                                                                                                                                                                   |
|:---------------:|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|    Conteúdo     | Um grupo de 4 amigos decide sobre o que vai ser falado no próximo episódio                                                                                                                                                                                                             |
|    Captação     | De forma a manter a qualidade num mínimo aceitável, gravamos cada episódio com os nossos smartphones. Atrevo-me a dizer que esta é a única coisa que não apresenta profissionalismo sem investimento                                                                                   |
| Ficheiros áudio | Cada episódio é editado com o software livre [Audacity](https://www.audacityteam.org/) e exportado para MP3 stéreo a 192kbps                                                                                                                                                           |
|   Alojamento    | Cada episódio é enviado para o [archive.org](https://archive.org)                                                                                                                                                                                                                      |
|    Feed RSS     | Foi criado novo código aberto para suportar completamente o feed RSS usado em _podcasting_ ([código no Github](https://github.com/marmita-de-redon/hugo-redon-podcast/blob/master/layouts/feed/rss.xml))                                                                               |
|  Site oficial   | Site feito em [Hugo - um _framework_ de sites estáticos](https://gohugo.io/) e alojado no [Github Pages](https://pages.github.com/) gratuitamente ([código no Github](https://github.com/marmita-de-redon/website))                                                                    |
|  Redes sociais  | Contas gratuitas em Instagram, Facebook, Twitter, Youtube, Github, Disqus                                                                                                                                                                                                              |
|      Marca      | As imagens vetoriais editadas em [Inkscape](https://inkscape.org/), com recurso a materiais do [Flaticon](https://www.flaticon.com/) e disponibilizado livremente em [Github](https://github.com/marmita-de-redon/brand). As cores são coerentes entre o site, imagens e redes sociais |
|  Estatísticas   | É possível obter [estatísticas básicas gratuitas](https://create.blubrry.com/resources/podcast-media-download-statistics/basic-statistics/) disponibilizadas pelo serviço Blubrry                                                                                                      |
|  Periodicidade  | Semanal - lançamentos na madrugada de sexta                                                                                                                                                                                                                                            |
|   Monetização   | Não feito                                                                                                                                                                                                                                                                              |
|      Plano      | Satisfação pessoal, ouvir os ouvintes e seguir o instinto &#128539;                                                                                                                                                                                                                    |

Adicionalmente o podcast [Marmita de Redon](https://marmita.pt) 
tem o seu código aberto, disponível para consulta (e sugestões para modificação)
em [github.com/marmita-de-redon](https://github.com/marmita-de-redon)

---

Este é o artigo #1 da série: [Como se faz um podcast](../como-se-faz-um-podcast):
{{< include "article-series/podcast.pt.md" >}}
