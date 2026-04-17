# RTFM Zig!  
_Read The Friendly Manual_  

---  

__So__ it turns out `zig` actually has really good documentation. Instead of 
using tutorials and "build x with zig" to learn `zig` I thought it would be 
best to read through it and build the examples. This repo allows that to be 
done offline - after zig is installed.  

I've included the `zig` source code as well as a `Containerfile` with the 
necessary dependencies to build a fully-functional `zig` binary. The 
`Containerfile` is/targets x64-archlinux but reading the `pacman` line should 
give you enough information about the dependencies to be able to build from 
source on other targets. Or, after building `zig` from source on x64-archlinux 
you should be able to use `zig` to build itself on alternate targets - I 
haven't tested this yet, but I'm certain someone has tested `zig`'s alternate 
targets before releasing the feature.  

### In this repository:  
    - `zig` source code  
    - `Containerfile` for building from source  
    - `doc/zig.html` _# Offline documentation_  
    - `zig std` _# Offline zig-std documentation - after building the binary_  
    - the examples in the documentation _# TODO_  
