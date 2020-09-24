# awesome-julia-desktop-app-makers
A list of possible ways to make desktop apps in Julia

| Tool                                                                                     | Windows Support   | Notes/Comment                                                                                        |
|------------------------------------------------------------------------------------------|-------------------|------------------------------------------------------------------------------------------------------|
| [Gtk.jl](https://github.com/JuliaGraphics/Gtk.jl)                                        | supposedly subpar | seems to work even on Windows but warns about being super slow                                       |
| [QML.jl](https://github.com/barche/QML.jl)                                               | Yes               | Seems to be pretty comprehensive. But it seems to require some time to compile due to its C++ origin |
| [MiniFB.jl](https://github.com/aviks/MiniFB.jl)                                          | Yes               | Doesn't have widget library, so likely to requires lots of foundational work                         |
| [GLFW.jl](https://github.com/JuliaGL/GLFW.jl)                                            | Yes               | Doesn't have widget library, so likely to requires lots of foundational work                         |
| [SimpleDirectMediaLayer.jl](https://github.com/jonathanBieler/SimpleDirectMediaLayer.jl) | Yes               | Commonly known as SDL2. Seems pretty low level                                                       |
| [Electron.jl](https://github.com/davidanthoff/Electron.jl)                               | Yes               | Electron-based, and seems to have significant start-up cost                                          |
| [Blink.jl](https://github.com/JuliaGizmos/Blink.jl)                                      | Yes               | Electron-based, and seems to have a significant start-up cost                                        |
