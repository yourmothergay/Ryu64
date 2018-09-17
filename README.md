# Welcome to Ryu64!
![alt](https://cdn.discordapp.com/icons/490752174461157379/58b8ba4423c43149036a2a1a1ace7c6d.png?size=256)

Hello, and welcome, to Ryu64!  This emulator aims to emulate the Nintendo 64, well, hopefully, right now it's just aiming to emulate the CPU of the Nintendo 64, the NEC vr4300 (aka the MIPS R4300i) don't expect much right now, nothing works at the time of writing this.  But hopefully, that is soon to change, if you want to help just make a PR, we'll be glad to accept improvements to the emulator.

## FAQ
### What does the name "Ryu64" derive from?
Simply put, the name just comes from the RyuJIT which is what .NET uses to run applications built in both Visual Basic and C#, we use the latter.
### Is there anywhere I can see your guys work on the emulator, and communicate, all in real time?
There is!  We have a discord where all the developers hang out, talk about development, etc.  [Join here.](https://discord.gg/3GQskCR)
### What is 86RYU?
86RYU is the x86 JIT currently developing along side this emulator, it aims to give some functionality C# it'd otherwise lack, aka, a functional x86 JIT that isn't RyuJIT and doesn't use MSIL.  For maximum efficiency the JIT is programmed in C, compiled using GCC, the GNU Compiler, then linked in via a DLL / SO.  The Github for that project is [here.](https://github.com/Ryu64Emulator/86RYU)

Okay hopefully that answered most of your questions, if it didn't, [join the discord and ask](https://discord.gg/3GQskCR), go ahead, don't be shy!
