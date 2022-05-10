# CKY-Parser

## NLP

Implementation of the CKY parser

## compiling

The steps to compile the command-line tester chart_tester are following:  
  
g++ -c CHART_hw_start.cpp -o CHART.o  
g++ -c chart_tester.cpp  
g++ chart_tester.o CHART.o rules.o -o chart_tester  
  
## testing

You should be able to reproduce the interactions which were described for the cgram and hit_eats_will_gram grammars.  
You could use the command-line program chart_tester, which is passed the grammar on the command-line:  
  
./chart_tester cgram.txt  
./chart_tester hit_eats_will_gram.txt  
　
