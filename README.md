#QTextEditor
##A simple text editor in pure QT

This is a basic Notepad clone in pure QT / C++ -it doesn't really use any custom C++ stuff.
It works with QT4 or QT5 

![Screenshot](https://cloud.githubusercontent.com/assets/3234333/5732653/830ee45e-9b4a-11e4-8361-df0a2c8bd204.png)


##To build

````
qtconfig-qt5 # or qtconfig-qt4 to build it for qt4
make
````

It produces a single binary called QTextEdit. You can then copy it to somewhere in your path

####To-do:
Set up default mimetype stuff

man xdg-mime
https://wiki.archlinux.org/index.php/xdg-open#Get_default_application

or just copy it from any mainstream text editor, like Juffed/Geany/Gedit
