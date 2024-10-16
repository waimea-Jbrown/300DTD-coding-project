# PROJECT NAME HERE

### Level 3 Programming Project by YOUR NAME HERE

This project is assessed against [AS91906](https://www.nzqa.govt.nz/nqfdocs/ncea-resource/achievements/2019/as91906.pdf)

## Project Description

The project involves the programming of a game. 

This game is a pick a path type game where you choose to either go north, south, east or west with each choice having an impact as well as having a lines of text telling the player what is in the room. the aim of the game is to find the exit escape the burning building which will be deteremind by an in-game timer of 2 two minutes and 30 seconds



## Source Code

The project is written in [Kotlin](https://kotlinlang.org/) and uses [Swing](https://docs.oracle.com/javase/8/docs/technotes/guides/swing/) for the GUI, themed with [FlatLAF](https://github.com/JFormDesigner/FlatLaf) for a modern look.

The main source file is [Main.kt](src/Main.kt)


## Documentation

Evidence of testing can be found in [testing.md](testing.md)


## Running the Program

You can either clone this whole repo, open it using [IntelliJ IDEA](https://www.jetbrains.com/idea/download/) and run from source; or you can run the compiled program:

1. Install the [Java runtime (JRE)](https://www.java.com/en/download/) installed to run the program.
2. Go to the [out/artifacts](out/artifacts) folder
3. Locate and download the compiled **JAR file** (e.g. FILENAME.jar)
4. Run the following command:
    ```bash
    java -jar FILENAME.jar
    ```