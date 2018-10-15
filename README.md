Fork of Box2D physics library without testbed, examples and docs (only library) and with restored CMake integration.
Orginal repo: https://github.com/erincatto/Box2D
## Versioning
This fork is versioned according to format: ``2.3.2-[commit-hash]``, where commit-hash is hash of latest commit from orginal repo.
Latest release of Box2D is 2.3.1, so treat this as a "development snapshot" of 2.3.2.
## Building:
```
mkdir build
cd build/
cmake .. [options]
make
sudo make install (if you want to install libs and headers)
```  
Note that this will compile debug version and static lib. If you want to build optimized release version use ``-DCMAKE_BUILD_TYPE=Release`` option. If you want to build shared library use ``-DBOX2D_BUILD_SHARED=ON`` option.


