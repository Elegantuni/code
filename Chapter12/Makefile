chapter12:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp -I../fmodlinux/api/lowlevel/inc -I../fmodlinux/api/studio/inc
	g++ -o chapter12 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image` `pkg-config --libs SDL2_ttf` -lGL -lGLEW -lSOIL -L../fmodlinux/api/lowlevel/lib/x86_64 -lfmod -L../fmodlinux/api/studio/lib/x86_64 -lfmodstudio
	
clean:
	rm -f chapter12 SDL *.o
	
