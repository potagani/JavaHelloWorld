#Quick setup — if you’ve done this kind of thing before

https://github.com/potagani/JavaHelloWorld.git

#create a new repository on the command line
mkdir javasamples
cd javasamples
mkdir JavaHelowWorld
git init 

touch HelloWorld.java
gedit HelloWorld.java

javac HelloWorld.java
java Helloworld.java

git add -A
git commit -m "first commit" *

git remote add origin https://github.com/potagani/JavaHelloWorld.git
git push -u origin master

#push an existing repository from the command line

git remote add origin https://github.com/potagani/JavaHelloWorld.git
git push -u origin master

