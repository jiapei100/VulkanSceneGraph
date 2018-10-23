
# VulkanSceneGraph introduction

The __VulkanSceneGraph__/__VkSceneGraph__ project is now under-way and will be a multi-year effort to develop an open source, next generation scene graph based on the Vulkan graphics API and modern C++.

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

## Prototype Phase underway

We are completed the __Exploration Phase__ and have established the main tools, depdendencies and techniques we'll use going forward. We are presently working the __Prototype Phase__, this is being done within the [VulkanSceneGraphPrototype](https://github.com/robertosfield/VulkanSceneGraphPrototype) repository. If we want to learn more details about the present work I would recommend browsing the VulkanSceneGraphPrototype reposotiry. Follows are a some direct links into this repository:

## Useful links within the VulkanSceneGraphPrototype:
* Software development [RoadMap](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterROADMAP.md)
* Design : [Principles and Philosophy](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterdocs/Design/DesignPrinciplesAndPhilosophy.md),  [High Level Decisions](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterdocs/docs/Design/HighLevelDesignDecisions.md)
* Community resources :  [Code of Conduct](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterdocs/CODE_OF_CONDUCT.md), [Contributing guide](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterdocs/CONTRIBUTING.md)
* Exploration Phase Materials : [Areas of Interest](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterdocs/ExplorationPhase/AreasOfInterest.md), [3rd Party Resources](https://github.com/robertosfield/VulkanSceneGraphPrototypedocs/docs/ExplorationPhase/3rdPartyResources.md) and [Exploration Phase Report](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterdocs/ExplorationPhase/VulkanSceneGraphExplorationPhaseReport.md)
* Headers - the public interface : [include/vsg/](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/masterinclude/vsg)
* Source - the implementation : [src/vsg/](https://github.com/robertosfield/VulkanSceneGraphPrototype/blob/mastersrc/vsg)



__Robert Osfield__, VulkanSceneGraph project lead, 1st June 2018
