Taak06: Websites-workflow
-------------------------

Algemeen
========

Voor deze opdracht was het de bedoeling dat wij een statische website maakten. Om deze niet van scratch te hoeven schrijven maakten we gebruik van een static-gen.
Na lang zoeken op staticgen en enkele hebben uitgeprobeerd, besefte ik al snel dat deze opdracht toch niet zo simpel is als ik eerst dacht. Vele van de static-gens waaronder hexo, 
octopress en pelican, werkten bij mij thuis helemaal niet of niet naar behoren.

Installatie
===========

Om deze static-site te maken heb ik gebruik gemaakt van de populaire `jekyll`. Deze static-gen is geschreven in *ruby* 
en maakt gebruik van *liquid* templates.

Om *jekyll* te installeren heb je eerst deze dingen nodig:


  * Ruby
  * RubyGems
  * Ruby DevKit
  
 
Als dit geïnstalleerd is kunnen we verder met *jekyll*. Open een `Administrator Command Prompt with Ruby` en voer de volgende commando's uit.

~~~ 
gem install jekyll
jekyll new projectname
cd projectname
jekyll serve
~~~
	 
Als je nu naar `localhost:4000` gaat in je browser, zul je de eerste versie van je static-site zien.


Configuratie
============

Eerst en vooral is het aangeraden om de *_config.yml* te bekijken, hierin kan je belangrijke zaken wijzigen zoals de titel van je site, de url .... en kan je verschillende instellingen toevoegen.


Pages toevoegen
===============

Om pages toe te voegen zijn er verschillende mogelijkheden. Ik heb telkens een .html file toegevoegd en daarin mijn taak in markdown verwerkt.
 Om deze markdown bestanden te renderen in een page moest ik eerst nog een plugin toevoegen. 



