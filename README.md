# Getting started (the best practice)

1. Visit https://julialang.org/downloads/ and get 1.9.2
2. (not recommended using Linux distribution installer, sometimes broken. Unless you're Arch user, then install `julia-bin` from AUR is fine)
3. clone this repo to a location you like
4. Run Julia executable, you will be dropped into a REPL:
```
$ > julia
               _
   _       _ _(_)_     |  Documentation: https://docs.julialang.org
  (_)     | (_) (_)    |
   _ _   _| |_  __ _   |  Type "?" for help, "]?" for Pkg help.
  | | | | | | |/ _` |  |
  | | |_| | | | (_| |  |  Version 1.9.2 (2023-07-05)
 _/ |\__'_|_|_|\__'_|  |  Official https://julialang.org/ release
|__/                   |

julia>
```
5. hit `;` once to switch to shell mode, cd to where you cloned this repo (you can cd before running
   `julia` in terminal, same effect)
6. hit `]` once to switch to Pkg mode, and run
```
pkg> activate .
```
where the `dot` means here.

7. run `pkg> instantiate`
8. Look at the screen again when waiting for precompilation
