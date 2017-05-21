# Unscented Kalman Filter Project Starter Code
Self-Driving Car Engineer Nanodegree Program

---

## Dependencies

* cmake >= v3.5
* make >= v4.1
* gcc/g++ >= v5.4

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./UnscentedKF path/to/input.txt path/to/output.txt`. You can find
   some sample inputs in 'data/'.
    - eg. `./UnscentedKF ../data/obj_pose-laser-radar-synthetic-input.txt`


## Result
When the algorithm runs against "obj_pose-laser-radar-synthetic-input.txt", the positions that the algorithm outputs are compared to ground truth data. The px, py, vx, and vy RMSE are [ 0.075, 0.094, 0.36, 0.28] less than the values [.09, .10, .40, .30].
