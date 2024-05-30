# Compiling The Code

There are a couple of methods for compiling and running the code:

- Launch 'Algorithm_Design_Homework/cmake-build-debug/Algorithm_Design_Homework.exe' by browsing it in File Explorer.

- Compiling the code with the [MinGW compiler](https://www.mingw-w64.org/downloads/), which must be installed locally. After installation, set a System Variable Path to MinGW's `bin` folder. To see if the installation worked, open Command Prompt and type `gcc --version`. If it worked, go to the root directory `Algorithm_Design_Homework` and run `gcc -o main.c utils.c`.

- In any compatible IDE, create a `blank project` and import the following files:`main.c`, `utils.c` and `utils.h`.
