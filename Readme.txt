--------------------------------------------------------------------------------
Building hello_world-1.0.0...
--------------------------------------------------------------------------------
Resolving build environment: python
resolved by ajohns@workstation.local, on Sun Jul 31 14:39:33 2016, using Rez v2.0.rc1.44

requested packages:
python
~platform==osx    (implicit)
~arch==x86_64     (implicit)
~os==osx-10.11.5  (implicit)

resolved packages:
arch-x86_64     /home/ajohns/packages/arch/x86_64                                            (local)
os-osx-10.11.5  /home/ajohns/packages/os/osx-10.11.5                                         (local)
platform-osx    /home/ajohns/packages/platform/osx                                           (local)
python-2.7.11   /home/ajohns/packages/python/2.7.11/platform-osx/arch-x86_64/os-osx-10.11.5  (local)

Invoking cmake build system...
Executing: /usr/local/bin/cmake -d /home/ajohns/workspace/rez/example_packages/hello_world -Wno-dev -DCMAKE_ECLIPSE_GENERATE_SOURCE_PROJECT=TRUE -D_ECLIPSE_VERSION=4.3 --no-warn-unused-cli -DCMAKE_INSTALL_PREFIX=/home/ajohns/packages/hello_world/1.0.0 -DCMAKE_MODULE_PATH=${CMAKE_MODULE_PATH} -DCMAKE_BUILD_TYPE=Release -DREZ_BUILD_TYPE=local -DREZ_BUILD_INSTALL=1 -G Unix Makefiles
Not searching for unused variables given on the command line.
-- Could NOT find PkgConfig (missing:  PKG_CONFIG_EXECUTABLE)
-- Configuring done
-- Generating done
-- Build files have been written to: /home/ajohns/workspace/rez/example_packages/hello_world/build

Executing: make -j4
[100%] Built target py

Executing: make -j4 install
[100%] Built target py
Install the project...
-- Install configuration: "Release"
-- Installing: /home/ajohns/packages/hello_world/1.0.0/./python/hello_world.py
-- Installing: /home/ajohns/packages/hello_world/1.0.0/./python/hello_world.pyc
-- Installing: /home/ajohns/packages/hello_world/1.0.0/./bin/hello

All 1 build(s) were successf
