# THP 08_crazy_scrapper
 
Hello co-moussaillon, pour vérifier mes 3 programmes : 

  > git clone https://github.com/140ch204/08_crazy_scrapper.git

  > cd 08_crazy_scrapper

  > rspec ./spec/scrapper_spec.rb   # pour Dark Trader

  > rspec ./spec/mairie_spec.rb     # pour Mairie christmas

  > rspec ./spec/deputy_spec.rb     # pour Cher député

  Enjoy ! 

En détail : 

2.2. Dark Trader

  Sujet : 

    Lehman Brothers, impressionnés par ton algorithme d'optimisation d'achat / vente, veut encore faire appel à toi. Leur Chief Digital Officer, très hype, a entendu parler au JT de TF1 d'un "truc révolutionnaire qui s'appelle le bloque-chienne". Il veut en acheter plein. Pour le conseiller, tu vas devoir récupérer le cours de toutes les cryptomonnaies du marché.

    En prenant pour source le site CoinMarketCap, fait un programme qui récupère le cours de toutes les cryptomonnaies et les enregistre bien proprement dans un array de hashs.

  Le testeur :

  > rspec ./spec/scrapper_spec.rb

  Le programme : 

  > ruby ./lib/scrapper.rb



2.3. Mairie christmas

  Le programme : 

  > ruby ./lib/mairie.rb

  Le testeur :

  > rspec ./spec/mairie_spec.rb

  Sujet : 

    Le CEO de Get-email Corp a besoin de tes services. Il voudrait toutes les adresses e-mail des mairies du Val d'Oise. Aucun souci pour toi. Va sur cet annuaire des mairies et récupère les adresses e-mails des mairies du Val d'Oise. Comme pour l'exercice précédent, tu devras enregistrer les données dans un array de hash suivant ce format : 

2.4. Cher député

  Le programme : 

  > ruby ./lib/deputy.rb

  Le testeur :

  > rspec ./spec/deputy_spec.rb

  Sujet : 

    Maintenant, fini de se faire mâcher le travail par tes gentils formateurs de THP. Tu dois récupérer la liste complète des députés de France ainsi que leurs adresses e-mail. Cherche par toi-même le site le plus aisé à scrapper et stocke les informations extraites dans une array de hashs selon ce format (un peu différent des exercices précédents) :


Enjoy ! 