git_pp.exe: git_pp.o
	g++ git_pp.o -o git_pp.exe
git_pp.cpp: klarasoliman.h MariamAli.h klarasoliman.cpp Mariamali.cpp main.cpp
	g++ -E klarasoliman.cpp MariamAli.cpp main.cpp -o git_pp.cpp 
git_pp.s: git_pp.cpp
	g++ -S git_pp.cpp -o git_pp.s
git_pp.o: git_pp.s
	g++ -c git_pp.s -o git_pp.o
