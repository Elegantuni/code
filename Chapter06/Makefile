chapter6:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp
	g++ -o chapter6 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image` -lGL -lGLEW -lSOIL
	
clean:
	rm -f chapter6 SDL *.o
	
