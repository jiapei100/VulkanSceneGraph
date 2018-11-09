
# VulkanSceneGraph introduction

The __VulkanSceneGraph__/__VkSceneGraph__ project is now under-way and will be a multi-year effort to develop an open source, next generation scene graph based on the Vulkan graphics API and modern C++17.  The home for new scene graph project is [https://github.com/vsg-dev](https://github.com/vsg-dev) so head there to see the latest work.

The project is under the auspices of Robert Osfield, principal author and project lead of the  __OpenSceneGraph__.  The new scene graph is the successor to the OpenSceneGraph, building upon all the knowledge and skills accumulated through the OpenSceneGraph's 20 years history.  The OpenSceneGraph and VulkanSceneGraph are both members of the same family, the DNA of the best elements of the OpenSceneGraph will be evident in the new scene graph. If you like the OpenSceneGraph we hope you'll love the VulkanSceneGraph.

The OpenSceneGraph will remain supported and will co-exist with the new scene graph for many years to come. While not API compatible the two scene graphs will evolve in parallel and development will be done in a way that will help application developers make the transition to the VulkanSceneGraph if and when they are ready.

Development of the VulkanSceneGraph will follow the spiral model of software development with three phases leading up to the 1.0 stable release. These phases will broadly be:

* __Exploration Phase__ :
Running June through Setember 2018 to research the technologies and techniques to be used (completed.) Work has fed directly into Prototype Phase

* __Prototype Phase__ (underway):
October through December 2018, will prototype the main scene graph classes with Vulkan support. Aim to have alpha functionality by the end of 2018.

* __Core Development Phase__ :
January 2018 onwards, will establish core scene graph classes with Vulkan support.  Aim to have beta quality software for Summer/Autumn 2019.

* __Relase Phase__ :
Timing depends upon preceeding pahses, with broad aim for 1.0 stable release later 2019. The core scene graph will be tested in graphics application development with refinements rather new features being the focus on work.

--

It's still very early days for the project, so far we have three projects, the vsg scene graph library, an osg2vsg utility library and a set of examples:

* [VulkanSceneGraphPrototype](https://github.com/vsg-dev/VulkanSceneGraphPrototype) - prototype for the Vulkan/VkSceneGraph library

* [osg2vsg](https://github.com/vsg-dev/osg2vsg) - utility library that can convert OpenSceneGraph image and scene graphs to VSG equivalents, enabling use of OpenSceneGraph image and model loaders

* [osgExamples](https://github.com/vsg-dev/osgExamples) - set of example programs that are being used initially to test functionality as it evolves, and then evolving into a example set to help developers learn how to use the VSG.

