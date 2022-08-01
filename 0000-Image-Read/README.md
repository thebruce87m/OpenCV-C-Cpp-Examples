

https://docs.opencv.org/4.x/db/df5/tutorial_linux_gcc_cmake.html

```bash

# Download the standard test image
wget https://upload.wikimedia.org/wikipedia/en/7/7d/Lenna_%28test_image%29.png -O ../Downloads/lena.png

mkdir build && cd build
cmake ../
make


./DisplayImage ../../Downloads/lena.png
```