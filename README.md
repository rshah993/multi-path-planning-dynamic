# multi-path-planning-dynamic
Path planning in unknown environments using a multi-agent system has been in demand in recent years with teams of robots sent in to uncharted environments among other applications. Here, we address the issue of planning a path to a goal location using a multi-agent network of robots in a partially known map and dynamic obstacles.

We propose an efficient algorithm like D* Lite for planning in partially known maps and environments with dynamic obstacles and extend it to a multi-robot system. We do not focus on complete coverage but rather on motion planning. We find ourselves at a crossroad in selecting the mode of communication between the robots with a centralized or a decentralized, distributed approach. A common problem with the centralized approach is that the network is dependent on a central robot, but on the other hand, a problem with the decentralized approach is computation complexity. We assume unrestricted communication for our problem.

It is essential for robust planning to take into account the inherent uncertainty with the obstacles in the problem, which arises due to uncertain localization, modeling errors, and disturbances. Prior work has handled the case of deterministically bounded uncertainty. We propose an alternative approach that uses a probabilistic representation of uncertainty for modelling obstacles with additive Gaussian noise that has known statistics.

The results were evaluated based on optimality, here it means shortest path with no collisions.

For more info, check the report.
