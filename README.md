# wrs_gazebo_worlds

The `wrs_gazebo_worlds` ROS package provides a collection of Gazebo worlds and models created using the official CAD data of the World Robot Summit.

**Content:**

*   [Getting Started](#getting-started)
*   [Submodule Integration](#submodule-integration)
*   [Contribution Guidelines](#contribution-guidelines)

## Getting Started

Add the Gazebo models of the `wrs_gazebo_worlds` ROS package to the `GAZEBO_MODEL_PATH` of your shell environment.

```shell
export GAZEBO_MODEL_PATH=${GAZEBO_MODEL_PATH}:/path/to/wrs_gazebo_worlds/models/
```

## Submodule Integration

Using HTTPS:

```shell
git submodule add -b master --name wrs_gazebo_worlds https://gitlab.com/naripa/wrs_gazebo_worlds.git catkin_ws/src/wrs_gazebo_worlds
```

Using SSH:

```shell
git submodule add -b master --name wrs_gazebo_worlds git@gitlab.com:naripa/wrs_gazebo_worlds.git catkin_ws/src/wrs_gazebo_worlds
```

Make sure that the `master` branch is tracked.

## Contribution Guidelines

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for details.
