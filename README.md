This is a fork of https://github.com/libretro/redream-next

Latest commits found from the following link:

https://web.archive.org/web/20201224070936/https://github.com/libretro/retrodream

The code has been modified to compile on the Jelos operating system

# redream

[redream](http://redream.io) is a work-in-progress SEGA Dreamcast emulator written in C for Mac, Linux and Windows.

redream is licensed under the GPLv3 license (see [LICENSE.txt](LICENSE.txt)) and uses third party libraries that are each distributed under their own terms (see each library's license in [deps/](deps/)).

## Downloading

The latest pre-built binaries can be found on the [downloads](http://redream.io/download) page.

## Building

Start by cloning the repository and setting up a build directory.

```
git clone https://github.com/inolen/redream.git
mkdir redream_build
cd redream_build
```

Next, generate a makefile or project file for your IDE of choice. For more info on the supported IDEs, checkout the [CMake documentation](http://www.cmake.org/cmake/help/latest/manual/cmake-generators.7.html).

```
# Makefile
cmake -DCMAKE_BUILD_TYPE=RELEASE ../redream

# Xcode project
cmake -G "Xcode" ../redream

# Visual Studio project
cmake -G "Visual Studio 14 Win64" ../redream
```

Finally, you can either run `make` from the command line if you've generated a Makefile or load up the project file and compile the code from inside of your IDE.

## Reporting bugs

Report bugs via the [GitHub issue queue](https://github.com/inolen/redream/issues).
