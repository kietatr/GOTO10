# GOTO10

My interpretation of the one-line Commodore 64 BASIC program: `10 PRINT CHR$(205.5+RND(1)); : GOTO 10`

Currently this only contains the C++ version. I will try to include other interpretations in different languages in the future.

# C++

``` cpp
#include <iostream> 
int main() { while(true) { std::cout << static_cast<char>(32 + 63*(rand()%2)); } }
```

# Some GIFs

### Morse code

The unfiltered version

<p align="center">
  <img src="./gifs/unfilteredMorseCode.gif" alt="Unfiltered Morse Code" width="800"/>
</p>

With some over-the-top GIPHY filters

<p align="center">
  
  <img src="./gifs/terminalOnSteroids.gif" alt="Glitchy Terminal On Steroids" width="800"/>

</p>
