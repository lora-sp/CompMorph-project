# CompMorph-project

## Implementing a finite-state transducer for Dharumbal
Dharumbal is an Aboriginal Australian language which has been declared extinct. This work is going to focus on the implementation of a finite state transducer using the Xerox Finite State Tools xfst and lexc. More precisely, the morphology of Dharumbal nouns and verbs is going to be implemented. The short grammar "Dharumbal: The language of Rockhampton, Australia", provided by Angela Terrill, is going to be the basis for the implementation decisions.

## Usage
Open the xfst interface and execute the command "source-dharumbal.script". The script-file will then automatically read the lexc-file, apply up the lower words and apply down the upper words. Note that comments and whitespaces contained in the files will appear as "???" in the interface.
