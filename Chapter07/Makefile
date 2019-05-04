chapter7:
	rm -f SDL
	ln -s /usr/include/SDL2 SDL
	g++ -c *.cpp -I../fmodlinux/api/lowlevel/inc -I../fmodlinux/api/studio/inc -I../fmodlinux/api/core/inc/
	g++ -o chapter7 `ls *.o` `pkg-config --libs sdl2` `pkg-config --libs SDL2_image` -lGL -lGLEW -lSOIL -L../fmodlinux/api/core/lib/x86_64 -lfmod -L../fmodlinux/api/studio/lib/x86_64 -lfmodstudio
	
clean:
	rm -f chapter7 SDL *.o
	
