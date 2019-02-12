# Stringer
Create localised string files for Android and iOS from a single CSV file.


### Working
1. Run `kscript Program.kt <Name of your csv file>.csv`. Files will be generated in the same directory.


*OR*
1. Create the csv named `KiteTabErrors.csv` and place it in `$homeDirectory/Downloads`. The resulting file path should be `$homeDirectory/Downloads/KiteTabErrors.csv`.
2. Execute [`main()`](https://github.com/GurpreetSK95/Stringer/blob/master/src/main/kotlin/com/gurpreetsk/Main.kt) function.
3. The generated files are located in `$homeDirectory/Desktop/KiteTabStrings` directory.


### TODOs
1. ~Convert to a kotlin script which can be run from terminal.~ Try fixing compilation errors and running main() using kscript.
2. Configurable source file path and destination folder.
3. Write missing tests - no TDD followed.
