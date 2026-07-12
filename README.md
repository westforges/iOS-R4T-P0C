# iOS Use-After-Free Research

[![Research Status](https://img.shields.io/badge/status-active--research-blue.svg)]()
[![Telegram Community](https://img.shields.io/badge/chat-Telegram-2CA5E0.svg)](https://t.me/iospentest)
[![Platform](https://img.shields.io/badge/platform-iOS-red.svg)]()


## What's this about?

Use-after-free = memory gets freed but something still holds a pointer to it and tries to use it. On iOS, that turns into:

- Kernel panics
- Breaking out of the sandbox
- Running code at kernel level
- Bypassing stuff like KASLR or PAC

Right now I'm focused on one specific UAF.


## Community

If you're into iOS internals, memory corruption, or exploit dev, come hang out:

### [Join](https://t.me/iospentest)

Good place to ask questions, share ideas, or just lurk and see what others are working on.

## Updates (eventually)
