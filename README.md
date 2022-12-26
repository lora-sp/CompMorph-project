# CompMorph-project

## Implementing a finite-state transducer for Dharumbal
Dharumbal is an Aboriginal Australian language which has been declared extinct. This work is going to focus on the implementation of a finite state transducer using the Xerox Finite State Tools xfst and lexc. More precisely, Dharumbal nominal and verbal morphology are going to be implemented. The short grammar "Dharumbal: The language of Rockhampton, Australia", provided by Angela Terrill, is going to be the basis for the implementation decisions.

## Usage
Open xfst and execute the command "source-dharumbal.script". The script-file will then read the lexc-files, apply up the lower words and apply down the upper words. Note that comments and whitespaces contained in the files will appear as "???" in the program.
