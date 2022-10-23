+++
author = "Aymeric"
title = "Le vignoble bordelais sèchera-t-il demain ?"
date = "2022-06-12"
description = "A propos de l'impact du réchauffement sur la viticulture."
categories = [
    "wine",
    "statistics"
]
tags = [
    "grapevine",
    "Bordeaux",
]
image = "Bordeaux-France.jpg"
+++

En 2013 une étude américaine menée par le professeur Lee Hannah a fait grand bruit : la température moyenne en climat méditerranéen dépassant de plus en plus les besoins de la vigne, de grandes zones deviendraient impropres à la viticulture dans les quarante années suivantes. Dix ans plus tard, la température s'est élevée, et pourtant, les abandons massifs de vignobles se font encore attendre. Qu’est-ce qui a donné tort à cette étude – jusqu’à maintenant du moins ?

## Chaleur et vigne

C’est que la relation entre température et qualité du vin est plus complexe qu’on ne le croyait alors. Pour mieux la comprendre, revenons au tout début de la production d’un millésime : le cycle de la vigne.

## Le cycle de la vigne

Cela commence comme une naissance, par des pleurs : après les premiers jours tièdes du printemps, la vigne sort de son sommeil hivernal, et sa sève s’écoule comme des larmes par les plaies qu’a laissées la taille. Alors les bourgeons sortent de leur bourre de coton pour commencer de croître. C’est après ce débourrement que le gel est dangereux, car la plante abaisse ses défenses contre le froid. Fin mai, les fleurs éclosent, puis s’enflent lentement en grains. Le fruit mûrit, se charge selon son cépage de sucre, de tannins, et pour le raisin noir, des anthocyanes qui le colorent.  Quand le raisin est mûr, on vendange, et la vinification commence au chai. Si chaque phase se passe sous des cieux cléments, et si la vigne peut croître, guidée par les inlassables travaux des vignerons, sans être ravagée par la grêle, le gel, le mildiou, ou par le pare-chocs d’un conducteur ivre sortant à grand fracas de la route des Châteaux, alors seulement le vin pourra être bon.

## La météo idéale

Au long de ce cycle, les conditions météorologiques idéales changent du tout au tout. L'hiver doit être froid pour que la vigne fasse ses réserves ; au contraire, pendant la maturation, le temps idéal est ce « soleil cuisant » que chantait l’âme du vin sous la plume de Baudelaire. Cette dernière condition est la plus importante : par exemple, faute de chaleir, le Cabernet-Sauvignon garde de lourds arômes de poivron vert qui déséquilibrent son bouquet. L’art des viticulteurs ne saurait se résumer au seul chiffre de la température, mais l’étude montre que les vins du siècle dernier furent en moyenne meilleurs après des étés chauds.
Un économiste américain, Orley Ashenfelter, mit cette relation en équation : il fut l’un des premiers à prédire que l’été 1982 très chaud et sec, donnerait naissance à une excellente année. Son compatriote, le jeune critique Robert Parker, fit aussi cette annonce audacieuse – et il y gagna une renommée mondiale, car 1982 leur donna raison, en se révélant progressivement comme l’un des grands millésimes du siècle.

## Les limites de la canicule

Pourtant, à des températures trop élevées, on ne peut plus faire de bon vin. A Bordeaux, l’été 2003 en est l’illustration : la canicule intense a bloqué la maturité des cépages - Merlot surtout, et donné des tannins trop mûrs. C'est dans cette idée que fut publiée l’étude de 2013, qui tablait sur un déclin de nos régions viticoles. Mais cette étude est allée trop loin dans ses conclusions, car elle prenait le climat comme seule force à l’œuvre. A l’époque, une lettre de contestation parut rapidement, menée par le professeur Van Leeuwen de l’institut de la Vigne et du Vin, qui pointait des erreurs méthodologiques, ainsi qu’une omission majeure : l’étude de Lee Hannah négligeait l’adaptation possible des modes de production.

## Repenser le travail de la vigne
« Le vin est le fils du soleil et de la terre, mais il a eu le travail comme accoucheur », disait Paul Claudel. Et pour adapter leurs méthodes au réchauffement climatique, les vignerons n’ont pas attendu les scientifiques. La viticulture mondiale foisonne d’idées nouvelles, et les grands crus bordelais sont depuis des dizaines d’années de véritables laboratoires à ciel ouvert. De nombreuses pratiques sont à l'essai : par exemple, laisser l’herbe pousser dans les rangs augmente l’albedo du sol – le rayonnement réfléchi vers le ciel au lieu d’être transformé en chaleur.

> Le projet scientifique Laccave s'est penché sur les adaptations au réchauffement dans le vignobles et produit [un recensement des adaptations à l'essai](https://paca.chambres-agriculture.fr/fileadmin/user_upload/Provence-Alpes-Cote_d_Azur/020_Inst_Paca/CRA_PACA/Documents/INNOVATION_RED_2017/Projet_LACCAVE.pdf).

Pablo Almaraz, chercheur de l’université de Cadiz, a montré l’impact tangible de cette adaptation. Il a étudié les relations entre la qualité du vin de Bordeaux, rapportée depuis plus d’un siècle par un courtier bordelais, et la température moyenne d’avril à septembre. Il est ainsi parvenu à obtenir une estimation de la température optimale : on obtient alors le graphe ci-dessous, où l’on voit que, depuis 1970, l’augmentation de température est précédée d’une augmentation progressive de la température optimale.



![almaraz](Almaraz.png)


Valeur en °C de la température moyenne à Bordeaux – en jaune (le trait continu est la courbe lissée) et de la température optimale calculée – en vert, avec les marges d’incertitude à 95% en vert plus clair. Graphe obtenu en reproduisant les étapes du travail de Pablo Almaraz avec la librairie Python pymc3.



## Conclusion


Alors, le vignoble de Bordeaux est-il voué au déclin ? Il semble que les travaux de la vigne – et sans doute aussi la vinification et l’élevage – ont su s’adapter avec un effet tangible. Mais ce n’est sans doute que du temps gagné, avant de toucher aux limites physiques de la vigne - rappelons que le scénario médian donné par [le dernier rapport du GIEC](https://www.ipcc.ch/report/ar6/wg1/downloads/report/IPCC_AR6_WGI_SPM_final.pdf) aboutit de manière _très probable_ à une augmentations globale de température supérieure à 2°C d'ici la fin du siècle, en particulier une augmentation de 4°C en Europe. Les températures au-dessus de 40°C peuvent dessécher les grappes et provoquer l’apoplexie des ceps. Les vignobles australiens et californiens sont déjà coutumiers de ces dégâts, et la France en a fait l’expérience douloureuse en juin 2019, quand un record de 45°C a été enregistré à Marsillac, séchant sur pied un tiers de la récolte de l’Hérault. 

D'autres dangers intensifiés par le réchauffement menaceront de plus en plus les vignobles : par exemple, le "goût de fumée" dont on a entendu parler en France en été 2022 quand la fumée des incendies de Gironde ont [survolé le vignoble bordelais](https://twitter.com/meteophile/status/1549110839172599810). 

Quoi qu'il en soit, le monde viticole a pleinement pris la mesure des menaces qui pèsent sur lui : [une stratégie nationale de la filière](https://innovin.fr/wp-content/uploads/2021/08/Strat%C3%A9gie-de-la-fili%C3%A8re-viticole-face-au-changement-climatique.pdf) a été construite par un partenariat incluant le grand organe de recherche agricole d'Etat, l'INRAE. Parmi les quatres scénarios possibles à l'horizon 2050, un scénario "nomade", qui impliquerait des relocalisations de vignobles, remettant en question le concept de terroir. Pour éviter que se réalise ce scénario, la filière devra s'appuyer sur nombre de piliers, dont le dernier revient à la racine du mal : puisque le réchauffement est un problème de société, et puisque la filière viticole demandera au gouvernement de l'aide dans les difficultés à venir, elle devra se montrer exemplaire dans l'atténuation du réchauffement.