<h1 align="center">
	<img src="https://img.icons8.com/cotton/2x/rope.png" width="150px"><br>
    bind - A bind-shell written in C.
</h1>
<p align="center">
	bind is a bind-shell, which is a type of shell that opens up a listener on a target machine. 
</p>

<p align="center">
	<a href="https://deno.land" target="_blank">
    	<img src="https://img.shields.io/badge/Version-1.0.0-7DCDE3?style=for-the-badge" alt="Version">
     </a>
	<a href="https://deno.land" target="_blank">
    	<img src="https://img.shields.io/badge/Deno-1.0.0+-7DCDE3?style=for-the-badge" alt="Node">
     </a>
</p>

## Setup
```
gcc -o bind bind.c
```

## Configuring Ports
```c
#include <stdio.h>
#include <stdlib.h>
#include <sys/types.h>
#include <sys/socket.h>
#include <netinet/in.h>

#define PORT 6965 // <- Go to this line in the file and change your port, if you want!
```

## Credits
```
https://github.com/0x1CA3
```

### Contributions 🎉
###### All contributions are accepted, simply open an Issue / Pull request.
