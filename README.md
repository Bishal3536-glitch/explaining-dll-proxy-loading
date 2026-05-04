here i explaind a dll proxy loader generator ,, the code i provided is origanted form the git repo-https://github.com/maluramichael/dll-proxy-generator
here is tried to explain the functions of the code , as i think it will help other people to learn it 
faster with out any headaches, 

let me clear one thing , the cpp code will generate two to three codes depending on the system , on 64 bit 
there will be two files one .cpp and one .def file ,, you can use visualstudio where .cpp is the main .dll code 
and the .def file the defining code for the dll declaraiton in the IAT

if the system is 32 bit there will be there codes one .cpp one .def and one is .asm ,, the asm is the defing code
of the 32 bit system , more about it is in the .txt file i provided.
