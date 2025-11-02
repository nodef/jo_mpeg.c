# jo_mpeg converted to C

jo_mpeg.cxx is a C++ simple, minimalistic, no allocations MPEG writer written as a [single header library][sfl] by [Jon Olick](https://www.jonolick.com/home/mpeg-video-writer), which creates [MPEG-1](https://en.wikipedia.org/wiki/MPEG-1) videos (without audio). It is listed as a C++ only library in stb’s single header library collection. However, only the `&` reference format is what makes this library C++ only. Replacing those with simple pointers makes this compile with both C and C++. Artsimovich is also a big fan of [stb-type of library code](https://github.com/nothings/stb?tab=readme-ov-file#why-single-file-headers), so he converted the library to C.

[sfl]: https://github.com/nothings/single_file_libs


## Installation

Run:
```bash
$ npm i jo_mpeg.c
```

And then include `jo_mpeg.h` as follows:
```c
#include "node_modules/jo_mpeg.c/jo_mpeg.h"
```

<br>
<br>


[![ORG](https://img.shields.io/badge/org-nodef-green?logo=Org)](https://nodef.github.io)
![](https://ga-beacon.deno.dev/G-RC63DPBH3P:SH3Eq-NoQ9mwgYeHWxu7cw/github.com/nodef/jo_mpeg.c)
