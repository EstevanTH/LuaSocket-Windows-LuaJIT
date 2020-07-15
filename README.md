# Windows builds for LuaSocket

The task is not very complicated to achieve yourself, but it requires quite some experience.

I give you my Windows Builds for LuaSocket (compiled against LuaJIT 2.0.5).

I do not know if it works with the official Lua 5.1.

I had to rebuild LuaJIT just to get the required `lua51.lib`, so I give it for download as well.

To build this LuaSocket with Visual Studio, do not build the whole solution at once. Build every projet one by one. After that, you can build the whole solution to finish up the process and confirm that everything worked.
