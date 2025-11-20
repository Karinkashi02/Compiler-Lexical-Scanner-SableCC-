# Compiler-Lexical-Scanner-SableCC-

How to install sablecc:

1. Unzip sablecc folder (put in C:\, to shorten the path)

2. Open your sablecc folder, click bin folder, copy the path and add to Environment Variables:

Search Environment Variables (Windows 10): go to System variables -> click Path -> edit -> new (add to list) -> OK

3. Copy path of java (jdk) to bin -> paste in Environment Variables

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

