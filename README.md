# CLiJavaApplicationExample

## Welcome to the Java Application Training Plugin Example, using only ```github CLI``` gh tool, and ```gradle CLI``` :

### Steps to the workflow :

#### Creating the Java App Using Gradle :

1-Generate a Java Application Sourcesets & buildScripts using gradle CLI using ```gradle init``` command in the project folder
<br>
2-Configure a manifest block inside the ```build.gradle``` to accept building ```jar``` files with the ```main.java``` class in mind
<br>
3-Compile & build files using ```build.gradle```
<br>
4-Run the raw java main class using ```./gradlew run``` 
<br>
5-Building a ```jar``` file for the SourceSets using ```gradle jar``` command or to zip files using ```gradle assemble```
<br>
6-Find the java jar build inside ```applicationExample/app/build/libs/app.jar``` & run it using ```java -jar app.jar``` to be sure of your results
<br>

#### Creating theb git repo & pushing files : 

1-run ```git init``` command in your root project directory, to initiliaze git local for this repo
<br>
2-run ```git add .``` command to add the current directory to the local it files inside ```.git``` folder in your root directory
<br>
3-run ```git commit -m "Commit Message``` to do commit the current files to the master branch
<br>
4-run ```gh repo create REPO-NAME``` to create a new empty git repository with the specified name
<br>
5-run ```git push origin main``` to push your code to the main origin branch
<br>


