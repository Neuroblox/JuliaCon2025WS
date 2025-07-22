# JuliaCon2025WS
Introduction to Neuroscience with Neuroblox.jl jupyter notebooks

# Install Instructions
using Pkg
pkg"registry add General" # add the Generl Registry, necessary to work with NeurobloxRegistry if this is the first time opening Julia
pkg"registry add https://github.com/Neuroblox/NeurobloxRegistry"; # add the Neuroblox Registry to the Julia registries to have access to Neuroblox.jl
Pkg.activate(@__DIR__) # activate a Julia environment at your current directory
Pkg.instantiate() # download all packages listed in the Project.toml we downloaded above
