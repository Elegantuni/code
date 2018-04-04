chapter2:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp
	g++ -o chapter2 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image`
	
clean:
	rm -f chapter2 SDL *.o
	
