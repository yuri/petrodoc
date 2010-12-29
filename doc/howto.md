
Petrodoc takes as input a single file that is similar to a LuaRocks rockspec
but contains additional fields for generating documentation.

For example, to generate documentation for [XSSFilter](http://spu.tnik.org/lib/xssfilter/),
we would use the following petrodoc file:

* https://github.com/yuri/lua-xssfilter/blob/master/petrodoc

We would go into "lua-xssfilter" directory and run petrodoc.lua
with "petrodoc" as the first argument.

This would give us:

* doc/index.html (see [XSSFilter](http://spu.tnik.org/lib/xssfilter/))
* a release file like xssfilter-10.12.28.tar.gz
* xssfilter-10.12.28-0.rockspec (a rockspec)


