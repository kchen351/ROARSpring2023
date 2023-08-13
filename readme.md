# Robot Open Autonomous Racing (ROAR)

This is the entry for the ROAR Spring 2023 competition that won 1st place!

Technical Report: https://roar.berkeley.edu/first-place-solution-in-spring-2023-simulation-racing-series/



Kevin Chen
How to run: 
Open the Berkeley Major Map folder, inside should be an application called CarlaUE4
Open application, then (I'm using Anaconda prompt, idk about other stuff) run runner_competition_evaluator.py by doing 
python runner_competition_evaluator.py

In order to re-write waypoints, go into runner_competition_evaluator.py, comment out the line importing "PIDFastAgent"
Uncomment the line importing the waypoint generator
In main(), change agent_class to the waypoint generating agent
Go into waypoint_generating_agent.py, change line 11 to be the backup file (or a completely new file)

In order to modify the code that controls the car, go to pid_fast_controller.py

