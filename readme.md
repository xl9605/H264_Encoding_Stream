Could NOT find SDL (missing: SDL_LIBRARY SDL_INCLUDE_DIR)
解决方案:sudo apt-get install libsdl-image1.2-dev libsdl-dev

确保build下没有任何文件,并且目录下没有cmakecache文件
build下cmake ..没错后make会在build下生成streamVideo的可执行文件
之后执行./streamVideo即可
内部可以设置一些参数,比如帧率,码率,分辨率
