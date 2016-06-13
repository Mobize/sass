SASS
===================

1. Télécharger et installer Ruby

	http://rubyinstaller.org

	> Pensez à cocher les cases à cocher :
	>  - Add Ruby executables to your PATH
	>  - Associate .rb and .rbw files with the Ruby installation

2. Puis dans gitbash OU cmd

	```
	gem install sass
	```

3. Une fois SASS installé

	- Créer un répertoire ``sass``
	- Ajouter les .scss

4. Puis lancer la compilation

	*Le paramètre watch permet de générer les css à chaque sauvegarde des fichiers .scss*

	```
	sass --watch sass:css
	```
	*sass --watch [SASS_WORKING_DIR]:[CSS_COMPILED_DIR]*