# Compiler-Lexical-Scanner-SableCC-

How to install sablecc:

1. Unzip sablecc folder (put in C:\, to shorten the path)

2. Open your sablecc folder, click bin folder, copy the path and add to Environment Variables:

Search Edit the system environment variables: 

in advanced tab go to Environment Variables -> click Path -> edit -> new e.g("C:\sablecc-3.7\bin") -> OK

3. Copy path of java (jdk) to bin "C:\Program Files\Java\jdk-25\bin" -> Click new on System Variables and paste on Variable Value and name anything you want

4. Open bin folder -> edit sablecc.bat file (Windows Batch File) -> copy path to lib folder -> paste in the absolute path

5. Run sablecc in DOS (cmd) 

COMMAND PROMPT COMMAND:
- cd to your sablecc main folder path
- Type "sablecc"
- Make changes on lexing.grammar file (Optional for upgrading)
- Make changes on lexing/Lexing.java (Only if necessary)
- Compile with commands:

java -jar lib\sablecc.jar lexing.grammar

javac lexing\node\*.java

javac lexing\lexer\*.java

javac lexing\analysis\*.java

javac lexing\Lexing.java

- Run the the sablecc with "java lexing.Lexing"
- Nothing will be shown (here where you type something like keywords, etc..)

