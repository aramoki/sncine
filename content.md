SNCINE
A GPU-driven Vulkan game engine and integrated editor written primarily in C/C++.


Features real-time rendering, scene streaming, asset packaging, physics, animation, Lua scripting, and a custom ImGui based editor.



1 Features
        1.1 Rendering
                - indirect forward + clustered pipeline
                - sparse gpu list handling
                - pbr rendering 
                - multiple textures , mesh ,
                - bilboard
                - decal
                - skeletal animation rendering
                - light probes 
                - hdr/ibl base rendering
                - compute based culling
                - swap chain image pacing consistency
                - cascaded directional shadow maps
                - local shadow maps
                - gpu based occlusion  culling (HZB and previous frame + conservative bias based on camera)
                - Order independent Approximate Weighted blended transparency
                - SSAO Basic Crytek Implementation, 
                - Bloom (UpSample -> DownSample Call of Duty implementation)
                - decals
                - particles
                - skeletal animation
                - BC Format textures and mipmapping
        1.3 Engine
                - Sparse list reference list
                - asset cache and streaming 
                - lazy file loading
                - user input/ output handling
                - lua script engine
                - skeletal animation
                - spartial partitioning
                        - grid base partitioning 
                - shadow bake
                - realtime shadows
                - Reverse-Z depth pipeline
                - Block Compression


        1.2 library
                - ibl calculation from hdr
                - equirectangular
                - linear algebra library
                - multi threading
                - Custom SNCPAK asset/package format
                        - Reference-counted asset cache
                        - Partition-based scene streaming
                        - Asynchronous loading and GPU transfers
                        - Project import/export functionality
        1.3 Editor
                - asset packing
                - gltf/ glb importing
                - sncpak export/import
                - sncpak asset package editing
                - object picking using stencil and aabb
                - animation selection
                - animation player




# Project at a glance
- Personal / Solo Engine Project 
- Developed since 2020
- 80% C language , editor is C++ 
- Vulkan based
- Cros platform (Windows , Linux and  macOS(with MoltenVK))
- 1,300+ commits
- 100K+ lines of engine, editor and shader code
- CTest for core library!
- Lua for scripting


# Benchmark And Test
Editor has cpu/gpu benchmark tool embedded in the engine and exports reports to txt file via editor. 
performans is real concern.
Engine development is targettet for variation of platforms and test are performed on devices below: 

always 60+ fps
Linux with Intel iGPU / Windows 1050Ti Gpu / Apple Radebon 5500m / Apple M5 Pro Apple Silicon Molten VK