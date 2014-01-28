LuaDataStructures
=================

Various data structures in Lua.

Some functional heaps (pairing, Fibonacci), and a few semi-implemented things (skip list, soft heap, union-find-delete trees), with intent to bring in a few more other things (ladder queue, 2-3 and / or trinomial heaps, relaxed weak heaps / queues, etc.) that I've been studying now and then.

A lot of what's already done could stand improvement to accommodate different versions of Lua (in particular, Lua 5.1 vs. 5.2 with its ephemerons vs. LuaJIT cdata). But it wasn't doing much good just sitting around in certain repositories, so this seems like a better place to park the data structures, perhaps facilitating later re-incorporation as submodules down the road.
