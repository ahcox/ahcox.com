

-   Main Khronos Vulkan page: <https://www.khronos.org/vulkan>, and
    [resources page](https://www.khronos.org/vulkan/resources).
-   The official Valve and LunarG Vulkan
    SDK: <http://lunarg.com/vulkan/>
-   Official assembler/disassembler for SPIR-V, the portable binary IR
    for Vulkan Shaders: <https://github.com/KhronosGroup/SPIRV-Tools/>
-   Khronos official [Vulkan
    resources](https://github.com/KhronosGroup/Khronosdotorg/tree/master/api/vulkan).
    Fork that and make a pull request to contribute.

### Vulkan Primers
-   [Baldurk's Introduction to Vulkan](https://renderdoc.org/vulkan-in-30-minutes.html)
-   [Henri Tuhola's Vulkan API Overview](http://boxbase.org/entries/2016/feb/22/vulkan-api-overview)
    -    [Rendering Primitives](http://boxbase.org/entries/2016/feb/29/vulkan-api-overview-2)
    -    [Pipeline Barriers](http://boxbase.org/entries/2016/mar/7/vulkan-api-overview-3)

### Vulkan Tutorials

-   API without Secrets: Introduction to Vulkan, by Pawel L., Intel, April 2016.
    -   [Part 0: Preface](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-preface)
    -   [Part 1: The Beginning](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-1)
    -   [Part 2: Creating a Swapchain](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-2)
    -   [Part 3: First Triangle](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-3)
    -   [Part 4: Vertex Attributes – Buffers, Images, and Fences](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-4)
    -   [Part 5: Staging Resources – Copying Data between Buffers](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-5)
    -   [Part 6: Descriptor Sets – Using Textures in Shaders](https://software.intel.com/en-us/articles/api-without-secrets-introduction-to-vulkan-part-6)
-   [ARM Mali Vulkan SDK Tutorials](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.0/tutorials.html)
    -   [Vulkan on Android](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.0/creatingVulkanWindow.html)
    -   [Hello Triangle](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.0/helloTriangle.html)
    -   [Multithreading in Vulkan](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.0/multithreading.html)
    -   [Compute Shaders](http://malideveloper.arm.com/downloads/deved/tutorial/SDK/Vulkan/1.0/basicCompute.html)
-   José Henriques
    -   [Vulkan 101](http://www.jhenriques.net/development.html)  
    -   [Shaders](http://www.jhenriques.net/vulkan_shaders.html)
-   [Vulkan-sxs](https://github.com/philiptaylor/vulkan-sxs) by Philip Taylor. Read the README.md in each sub-folder.
    -   [Creating a Device](https://github.com/philiptaylor/vulkan-sxs/blob/master/01-device/README.md)
    -   [Clearing the Screen and Memory Dependencies](https://github.com/philiptaylor/vulkan-sxs/blob/master/04-clear/README.md).

### Vulkan Wrappers, Helpers, and Utility Libraries

-   [Khronos C++ Wrapper](https://github.com/KhronosGroup/Vulkan-Hpp/blob/master/README.md):
    Originally a side project of a member of the NVIDIA workstation graphics team,
    this C++ wrapper gives a safer interface than the raw C API,
    some help with RAII for API objects, and optional exceptions.
-   [ARM Mali PerfDoc](https://github.com/ARM-software/perfdoc):
    A standard Vulkan `Layer`, able to run over any Vulkan implementation,
    which checks for performance pitfalls specific to ARM Mali.
-   [VKTS (VulKan ToolS) library](https://github.com/McNopper/Vulkan),
    by [Norbert Nopper](https://twitter.com/McNopper).
-   [Vulkano](https://github.com/tomaka/vulkano): A Rust language
    wrapper for Vulkan by [Tomaka](https://www.reddit.com/user/tomaka17)
    who has [worked with Mantle](https://github.com/tomaka/mantle-demo).
-   [OpenFrameworks Vulkan Renderer](https://forum.openframeworks.cc/t/vulkan-renderer/23800):
    Provides a GL-like context interface over Vulkan.   

### Example Vulkan Code

-   [Norbert Nopper](https://twitter.com/McNopper): [Samples using VKTS
    (VulKan ToolS) library](https://github.com/McNopper/Vulkan).
-   [Sascha](http://www.saschawillems.de/)
    [Willems](https://twitter.com/SaschaWillems2): [Vulkan examples and
    demos](https://github.com/SaschaWillems/Vulkan).
-   [Google Android Samples](https://github.com/googlesamples/android-vulkan-tutorials)

### Presentations on Vulkan
 - Migrating from OpenGL to Vulkan, Mark Kilgard, NVIDIA, January 19, 2016. [PDF](http://on-demand.gputechconf.com/gtc/2016/events/vulkanday/Migrating_from_OpenGL_to_Vulkan.pdf)
 - C++ API Layer on top of Vulkan, Markus Tavenrath, NVIDIA, 2016. [PDF](http://on-demand.gputechconf.com/gtc/2016/events/vulkanday/Vulkan_C++.pdf)
 - High Performance Vulkan: Lessons Learned from Source 2, John McDonald, Valve, 2016. [PDF](http://on-demand.gputechconf.com/gtc/2016/events/vulkanday/High_Performance_Vulkan.pdf)
 - Vulkan Overview and Roadmap for NVIDIA GPUs, Piers Daniell, NVIDIA, January 19 2016. [PDF](https://developer.nvidia.com/sites/default/files/akamai/gameworks/VulkanDevDaypdaniel.pdf)

### Projects Using Vulkan
-   [Hatchit](https://github.com/thirddegree/Hatchit): Open Source 3D Game Engine rendering through Vulkan and DX12. [Vukan Headers](https://github.com/thirddegree/HatchitGraphics/tree/master/include/vulkan). [Vulkan Implementation Code](https://github.com/thirddegree/HatchitGraphics/tree/master/source/vulkan).

### Discussion & Q&A

-   NVIDIA Gameworks [Vulkan
    Board](https://devtalk.nvidia.com/default/board/166/)
-   The [official
    forum](https://www.khronos.org/message_boards/forumdisplay.php/114-Vulkan-High-Efficiency-GPU-Graphics-and-Compute).
-   Stack Overflow [Vulkan
    tag](http://stackoverflow.com/questions/tagged/vulkan)
-   Reddit [/r/vulkan](https://www.reddit.com/r/vulkan/).

### Other Vulkan Resource Pages

-   Roundup of Vulkan information by Alexander Overvoorde, the author of
    [open.gl](https://open.gl/): <http://vulkan-tutorial.com/>
-   Another roundup of Vulkan information by
    [TheBuzzSaw](https://www.reddit.com/user/TheBuzzSaw):
    <https://sites.google.com/site/cachefriendly/vulkan>
-   Yet another [Vulkan link
    roundup](http://renderingpipeline.com/2015/03/vulkan-links) by
    Renderpipeline ([Robert
    Menzel](https://twitter.com/renderpipeline)).
-   jcoder58's [Vulkan Resources](https://github.com/jcoder58/VulkanResources).

### Prerelease Information
-   *[PRERELEASE]*Loads of code and information in these SIGGRAPH 2015
    Presentations - An Overview of Next-Generation Graphics APIs, "This
    introductory course provides an overview of switching from current
    to next-gen APIs; discusses similarities between next-gen APIs;
    covers basic API details for DirectX12, Vulkan, etc.; explores
    specific case studies from developers working with these APIs":
    <http://nextgenapis.realtimerendering.com/>
-   *[PRERELEASE]*[Imagination Technology Vulkan
    Webinars](http://blog.imgtec.com/powervr/5-new-webinars-on-the-vulkan-api)
    (Videos and blog posts)
    -   *[PRERELEASE]*[Vulkan: One API for all
        Platforms](http://blog.imgtec.com/powervr/vulkan-one-api-for-all-platforms),
        by Tobias Hector of Imagination Technology, October 19th 2015.

#### Prerelease Videos

-   November 2015, [Vulkan: Scaling to multiple
    threads](https://www.youtube.com/watch?v=s3ub6iVThro&t=2m35s), by
    Tobias Hector of Imagination Technologies
-   November 2015, [Vulkan: High efficiency on
    mobile](https://www.youtube.com/watch?v=4exq7Pb0XRo), by Tobias
    Hector of Imagination Technologies
-   October 2015, [Vulkan: One API for all
    platforms](https://www.youtube.com/watch?v=eDp7CFw-UPE), by Tobias
    Hector of Imagination Technologies
-   [August 2015, Vulkan on NVIDIA GPUs, by Piers
    Daniell](https://www.youtube.com/watch?v=NqensKmmRfE)
-   [August 2015, 3D Graphics API State of the Union, Vulkan Status
    Update at
    SIGGRAPH](https://www.youtube.com/watch?v=quNsdYfWXfM&t=55m21s)
-   [March 2015, Vulkan and SPIR-V Session at
    GDC](https://www.youtube.com/watch?v=qKbtrVEhaw8)
-   [March 2015, Vulkan - The Future of High Performance Graphics, at
    GDC](https://www.youtube.com/watch?v=QF7gENO6CI8&)
    -   [Johan Andersson, Introducing
        Vulkan](https://www.youtube.com/watch?v=QF7gENO6CI8&t=03m10s)
    -   [Pierre-Loup Griffais of Valve on High Level Concepts in
        Vulkan](https://www.youtube.com/watch?v=QF7gENO6CI8&t=08m42s)
    -   [Dan Baker on Vulkan and Many
        Threads](https://www.youtube.com/watch?v=QF7gENO6CI8&t=20m0s)
    -   [Niklas Smedberg of Epic Games, Vulkan Binding
        Model](https://www.youtube.com/watch?v=QF7gENO6CI8&t=32m38s)
    -   [Aras Pranckevičius of Unity on Vulkan shaders and
        SPIR-V](https://www.youtube.com/watch?v=QF7gENO6CI8&t=39m36s)
    -   [John McDonald of Valve on Layers, Loader, SDK, and tools for
        Vulkan line the GLAVE
        debugger](https://www.youtube.com/watch?v=QF7gENO6CI8&t=50m33s)
    -   [Q&A](https://www.youtube.com/watch?v=QF7gENO6CI8&t=63m35s)
-   [March 2015, Oxide Games Show Their Game, Engine, and a only a tiny
    bit about Vulkan (basically just that they are using
    it)](https://www.youtube.com/watch?v=ljeBu7-vKI4&t=1m32s)

[Edit this resource list](https://github.com/ahcox/ahcox.com/edit/master/vulkan/resources.md).
