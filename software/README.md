# Software

The project plans to run vision, pose estimation and target selection on a Linux host. The real-time controller will handle encoder acquisition, wheel-speed feedback, intake control and the command watchdog.

The target selection sequence is search, align, capture and confirm. A failed capture stops the rover and allows a bounded retry if the recovery path is clear. The team will use a Python Kiwi-drive model to test the effect of wheel slip on encoder odometry before hardware tuning.
