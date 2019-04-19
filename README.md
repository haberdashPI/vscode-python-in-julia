# Python in Julia 

[Python](https://www.python.org/) syntax highlighting
inside [Julia](http://julialang.org) within
[PyCall.jl](https://github.com/JuliaPy/PyCall.jl) strings (e.g. py"x =
x + 1").

## Requirements

- A python language extension
- The [Julia language extension](https://marketplace.visualstudio.com/items?itemName=julialang.language-julia)

## WARNING

Until 0.11.6 of the julia language extension comes out, this extension will
not work properly due to a bug in syntax highlighting for Julia. You can
manually download and install the latest master by
[following the instructions here](https://github.com/JuliaEditorSupport/julia-vscode/wiki/Updating-to-the-lastest-julia-vscode)