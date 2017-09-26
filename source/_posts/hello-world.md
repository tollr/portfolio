---
title: en quelques mots
foreword: Présentation du blog et d'Hexo
tags: hexo, static website, cli
---

## en quelques mots

Commençons par le début, ceci est blog créé grâce à [Hexo](https://hexo.io), un générateur de site statique. L'idée principale étant d'avoir un outil facile à mettre à jour pour parler le plus régulièrement possible de mes projets. 

Hexo est un outil plutôt simple à prendre en main et possède une galerie assez fournie de thèmes qui s'installent par un simple git clone dans le dossier dédié. La customisation du thème, ou la création d'un nouveau semble elle aussi assez simple. Sur le thème que j'utilise [again](https://github.com/lyyourc/hexo-theme-again) les templates sont rédigés suivant une syntaxe .ejs et le style via le préprocesseur css SASS. 

	📁 again
		📁 layout
			📁 _partial
				📃 header.ejs
				📃 ...
		📃 layout.ejs
		📃 ...
		📁 source
			📁 css
				📃 base.scss
				📃... 
			📁 js
				📃 app.js
				📃 ...
			📁 images
	📃 config.yml			

L'intérêt assez évident étant celui du site statique : on se passe de base de données, de configuration backend pour se concentrer sur le contenu du site.

Pour de plus amples informations, le plus simple étant peut-être d'aller sur leur [site](https://hexo.io) ou leur [Github](https://github.com/hexojs/hexo). 