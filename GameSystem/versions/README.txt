To install new versions (for example: 1.12.2) :
==================================================

1. Create new directory named as version's name (here, 1.12.2)

2. Put version JAR into this new directoy named as "<version>.jar"
	(for 1.12.2, the file will be named "1.12.2.jar")

3. Put all natives libraries into "natives" directory
	(located in the previously created folder)

4. Create new text file "<version>-libraries.txt" where, every line contains the relative
	path to access to library's file (relative from "libraries" folder).

	For example, to append "com.mojang:authlib:1.5.25" into classpath, will add new line like this:
-----------------------
com/mojang/authlib/1.5.25/authlib-1.5.25.jar
-----------------------
	And you repeat this for any libraries version need...

5. (Optional) To append game's asset : 
	a. You will need to add assets' indexes into "assets/indexes" (index file is named as "version.json")
	b. Copy all objects into "assets/objects"


===========
Et voilà ! 
