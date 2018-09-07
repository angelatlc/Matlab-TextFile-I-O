# Matlab-TextFile-I-O
This matlab function reads a file, processes the data, and writes a new file.

## Basic Operation
- The function prompts the user to pick an input folder and an output folder.
- Raw txt files in the user-selected folder are automatically read (a sample files is included in this repository for testing).
- Non data columns and any rows with NaN values are removed.
- The data columns are input to a table.
- Data table is sorted by rbg column category.
- Data is written to a tab-delimited txt file which has the same name as the input file plus '_Output'.

## Other Features
- A table is generated upon reading the input file (currently commented out).
- Able to plot all data or data based on rbg category to the same axis.
