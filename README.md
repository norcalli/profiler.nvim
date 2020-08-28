# Usage: 

```
luafile /home/ashkan/works/profiler.nvim/lua/profiler.lua
lua require 'init'
```

sets a global function `WRAP(fn)` which wraps a function to be timed or
`M(name, fn, ...)` which executes the function with the name.

By default, `require` will be wrapped.

Now run `env AK_PROFILER=1 nvim 2>&1 >/dev/null | less`
