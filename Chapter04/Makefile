chapter4:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp
	g++ -o chapter4 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image`
	
clean:
	rm -f chapter4 SDL *.o
	
