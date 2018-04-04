chapter1:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp
	g++ -o chapter1 `ls *.o` `pkg-config --libs sdl2`
	
clean:
	rm -f chapter1 SDL *.o
	
