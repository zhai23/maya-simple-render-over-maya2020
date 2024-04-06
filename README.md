# maya-simple-render-override
A simple C++ plugin showing how to plot screen-space trajectories/motion-trails via Maya Viewport 2.0 Render Override. 

### Build with CMake

Make sure to set environment variable `DEVKIT_LOCATION` to the installed path before running CMake.

### Usage

Once the plugin is built and loaded, you can access `Simple Render Override` in the "Renderer" drop-down menu on the 3-D viewport.

The plugin also provides a command `simpleTrack` to allow you to specify the selected object for tracking, as well as flags to modify the visuals:
- **clear**: remove all tracking objects.
- **numOfFrames**: number of frames before & after the current frame you wish to plot the trajectories.
- **pointSize**: size of the points of the trajectories.
- **screenSpace**: option to plot the trajectories in screen space (true) or world space (false).
![](https://github.com/zhai23/maya-simple-render-over-maya2020/blob/main/%E5%B1%8F%E5%B9%95%E6%88%AA%E5%9B%BE%202024-04-06%20180359.png)
