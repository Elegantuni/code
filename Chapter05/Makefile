chapter5:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp
	g++ -o chapter5 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image` -lGL -lGLEW -lSOIL
	
clean:
	rm -f chapter5 SDL *.o
	
