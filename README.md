# Visual-Comparison-on-Sample-Maps
Visual Comparison on Sample Maps
Welcome to the interactive gallery showcasing how each planner navigates two representative urban scenarios:

Static Map (Scenario 7)

Dynamic Map (Scenario 9)

Highlights
A*

Deadlocks and collisions appear in dynamic scenes.

Task‐assignment can cause “crossed” paths when computational constraints force non-nearest UAV choices.

D* Lite

Incremental replanning avoids some static deadlocks but still succumbs to moving obstacles, resulting in zig-zag and hesitation near high-risk zones.

CBS-D*

Resolves inter-agent conflicts effectively, but its high‐level conflict-tree updates produce pronounced detours and occasional mid-segment collisions.

PSO

Continuous, smooth trajectories that avoid obstacles, yet global sampling sometimes loops unnecessarily, trading path length for exploration.

PAIR

Seamlessly integrates A*’s fast backbone with PPO-based local corrections.

In both static and dynamic environments, it maintains safe separation, minimal detours, and instant reaction to intrusions—demonstrating the best balance of responsiveness and optimality.

