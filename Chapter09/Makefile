chapter9:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp -I../fmodlinux/api/core/inc -I../fmodlinux/api/studio/inc
	g++ -o chapter9 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image` -lGL -lGLEW -lSOIL -L../fmodlinux/api/core/lib/x86_64 -lfmod -L../fmodlinux/api/studio/lib/x86_64 -lfmodstudio
	
clean:
	rm -f chapter9 SDL *.o
	
