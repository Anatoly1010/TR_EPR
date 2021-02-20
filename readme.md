# Time-Resolved Electronic Paramagnetic Resonance Data Treatment

## Requirements
- [Wolfram Mathematica 11+](https://www.wolfram.com/mathematica/)

## Basic usage

1. Wolfram Mathematica

Install the Wolfram Mathematica version 11 or higher.

2. Global options for initialization cells

In Wolfram Mathematica press:

    Ctrl + Shift + O

In "Show option values" select:

    Global Preferences

In "Notebook Options - Evaluation Options" change:
    
    InitializationCellEvaluation -> True
    InitializationCellWarning -> False
    GlobalInitializationCellWarning -> False

Press "Apply".

3. Directories

Open the TR_ESR program in Wolfram Mathematica. Modify the specifeied two lines according to your preference for opening directories:

    dirExpData = SetDirectory["D:/Melnikov/00_Experimental_Data/2020/FEL"];
    dirSaveData = FileNameJoin[{"D:/Melnikov/00_Experimental_Data/", "2020/FEL/"}];

The first directory will be opened when you click the "Open file" button. The second directory opens when you click the "Save data" button.

4. Manual

A brief description of the available functions is given in the file "Commands_manual.txt".

