LÖVE is an awesome framework you can use to make 2D games in Lua. It's free, open-source, and works on Windows, Mac OS X and Linux.
Documentation
We use our wiki for documentation. If you need further help, feel free to ask on our forums, and last but not least there's the irc channel #love on OFTC.
Compilation
Windows
Use the project files for Visual Studio 2010 located in the platform dir.
*nix
Run platform/unix/automagic, then run ./configure and make.
OSX
Use the XCode project in platform/macosx.
For both Windows and OSX there are dependencies available here.
Repository information
We use the 'default' branch for development, and therefore it should not be considered stable. Also used is the 'minor' branch, which is used for features in the next minor version and it is not our development target (which would be the next revision). (Version numbers formatted major.minor.revision.)
We tag all our releases (since we started using mercurial), and have binary downloads available for them.
Builds
Releases are found in the 'downloads' section on bitbucket, are linked on the site, and there's a ppa for ubuntu, ppa:bartbes/love-stable.
There are also unstable/nightly builds:
For windows they are located here.
For ubuntu linux they are in ppa:bartbes/love-unstable
For arch linux there's love-hg in the AUR.
For other linuxes and OSX there are currently no official builds.
Dependencies
SDL
OpenGL
OpenAL
Lua / LuaJIT / LLVM-lua
DevIL with MNG and TIFF
FreeType
PhysicsFS
ModPlug
mpg123
Vorbisfile