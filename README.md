# CLiJavaApplicationExample

## Welcome to the Java Application Training Plugin Example, using only ```github CLI``` gh tool, and ```gradle CLI``` :

### Steps to the workflow :

>#### Creating the Java App Using Gradle :

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

>#### Creating the git repo & pushing files : 

1-run ```git init``` command in your root project directory, to initiliaze git local for this repo
<br>
2-run ```git add .``` command to add the current directory to the local it files inside ```.git``` folder in your root directory
<br>
3-run ```git commit -m "Commit Message``` to do commit the current files to the master branch
<br>
4-run ```gh repo create REPO-NAME``` to create a new empty git repository with the specified name
<br>
5-run ```git checkout -b main``` to switch from the branch(```-b```) to a new branch named ```main``` (it will create it anyway)
<br>
6-run ```git push origin main``` to push your code to the ```main``` origin branch
<br>

### ```eg ``` :

```bash
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git init
Initialized empty Git repository in /home/twisted/GradleProjects/applicationExample/.git/
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
	add
┌─[✗]─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git add .
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git commit -m "Initial Commit"
[master (root-commit) a755c89] Initial Commit
 10 files changed, 364 insertions(+)
 create mode 100644 .gitattributes
 create mode 100644 .gitignore
 create mode 100644 app/build.gradle
 create mode 100644 app/src/main/java/javaApp/App.java
 create mode 100644 app/src/test/java/javaApp/AppTest.java
 create mode 100644 gradle/wrapper/gradle-wrapper.jar
 create mode 100644 gradle/wrapper/gradle-wrapper.properties
 create mode 100755 gradlew
 create mode 100644 gradlew.bat
 create mode 100644 settings.gradle
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $gh repo create CLiJavaApplicationExample
? Visibility Public
? This will add an "origin" git remote to your local repository. Continue? Yes
✓ Created repository Scrappers-glitch/CLiJavaApplicationExample on GitHub
fatal: Unable to find remote helper for 'https'
error: Could not fetch origin
/snap/gh/345/usr/bin/git: exit status 1
┌─[✗]─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git checkout -b main
Switched to a new branch 'main'
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $git push origin main
Username for 'https://github.com': scrappers.tm@gmail.com
Password for 'https://scrappers.tm@gmail.com@github.com': 
Enumerating objects: 22, done.
Counting objects: 100% (22/22), done.
Delta compression using up to 4 threads
Compressing objects: 100% (15/15), done.
Writing objects: 100% (22/22), 57.63 KiB | 2.74 MiB/s, done.
Total 22 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Scrappers-glitch/CLiJavaApplicationExample.git
 * [new branch]      main -> main
┌─[twisted@parrot]─[~/GradleProjects/applicationExample]
└──╼ $
```
