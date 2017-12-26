## µSockets - the composable TCP library

µS is a lightweight & speedy cross-platform TCP library with composable implementation layers.
If you're feeling lucky, it also comes with its own experimental user-space TCP stack - compose your TCP as if it were a Subway sandwich!

Planned layers:

* Socket layers: BSD, WinSock, mTCP, µSockets
* Event layers: Epoll, Kqueue, Libuv, ASIO

Design goals:

* Minimal, easy-to-use, async-only, symmetric interface.
* Very lightweight & speedy (foundation of µWebSockets).
* Can be made to fit in almost everywhere via layered design.
* Has its own experimental user-space TCP stack (ongoing project).
