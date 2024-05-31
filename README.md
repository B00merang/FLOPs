# Extending Project Pegasus: PEGAFLOPs
An open-source repository of Foliage tools for Houdini called **Flora**, expanding on the tools shown off in [Part 11](https://www.sidefx.com/tutorials/project-pegasus-flora/) of [Project Pegasus for Houdini](https://www.sidefx.com/pegasus/)!

## About
FLOPs is a digital asset library for SideFX's Houdini extending on the tools shown in the Project Pegasus Flora section. Flora itself uses many simulation points to create highly customizable, and incredibly realistic 3D foliage. 

FLOPs is **open source software**, free to use for anyone, forever!

## Tools

- **Clip by Attribute**
    - Utilize **rest** nodes to prune points and segments based on an attribute. *e.x., simulate branch growth by pruning points based on the arc distance from root.*

- **Longest Path**
    - Recursively identify the longest set of connected edges, this is especially useful for primitive optimization, and creating high quality meshes.

## Installation
If you are unfamiliar with Houdini Packages, this section will give you a easy way to jump into the FLOPs nodes!
1. Navigate to the *~/FLOPs/Houdini20.0/HIPs/* path. These are the example project files for all the important FLOPs tools.
2. Once you choose a project file and open it, navigate to the **+** next to the Geometry Spreadsheet tab, expand **New Pane Tab Type -> Inspectors -> Package Browser**
3. Once you have the Package Browser open, go to **File -> Load Package..**, and choose the *~/FLOPs/Houdini20.0/packages/pegaflops.json*
4. **You are set! Lots of nodes use the timeline to control the nodes by default, check before reporting!**

*Make sure to redo this process for any of the HIPs you open! they are not configured to know where the dependency OTLs are at install, you need to install the package for each HIP!*

## Further Resources!
FLOPs has WiP documentation, feel free to open bug reports, RFEs (Request for Enhancement), or feedback of any kind. [Our issue tracker is here!](https://github.com/B00merang/FLOPs/issues?q=is%3Aopen)
