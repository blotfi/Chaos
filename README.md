# Chaos

Les fichiers qui ont servi à générer les animations et figures de ma vidéo sur le chaos
https://www.youtube.com/watch?v=YrOyRCD7M14

Ils sont là uniquement pour info, pour ceux qui connaissent déjà Python. Je n'ai malheureusement pas le temps d'assurer le service après vente :-)

A savoir :
* Tous les fichiers sont indépendants les uns des autres, et sont plus ou moins numérotés dans l'ordre où ils apparaissent dans la vidéo
* Il faut avoir les packages scientifiques "classiques" : numpy, scipy, matplotlib...je recommande les distributions qui contiennent déjà tout ce qu'il faut comme Anaconda ou Winpython
* Pour générer les films, il faut avoir installé ffmpeg quelque part sur votre disque, et renseigné son chemin dans chaque fichier, au niveau de la ligne :

plt.rcParams['animation.ffmpeg_path'] = r'/Volumes/Data/Youtube/[ffmpeg]/ffmpeg'

Bonne chance :-)

David

------------------------------------
Merci David pour les .py
je sais que tu as dit que tu n’assurais pas le SAV
Je propose juste une adaptation pour ceux qui ont un PC/Windows
Donc, qqes modifs utiles pour le lecteur qui veut essayer tes fichiers
il faut modifier le chemin où est installé ffmpegexe et indiquer aussi celui de la sauvegarde

plt.rcParams[‘animation.ffmpeg_path’] = ‘e:/uz/ffmpeg/bin/ffmpeg.exe’

movie_file = ‘e:/temp/02-canon_poly.mp4’

ani.save( movie_file, writer = writer)

Bonne adaptation

Lotfi
