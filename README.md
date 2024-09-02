# EE352: Advanced Control Systems - Term Project Summary

## Project Summary

The project focused on stabilizing a camera mounted on a stick, where the base of the stick moves along the x-axis. The key objectives were:

1. **Proportional Feedback Control:**
   - Determined if the system could be stabilized with proportional feedback.
   - Analysis showed that proportional feedback alone could not stabilize the system, as it resulted in instability.

2. **State-Feedback Control:**
   - Designed a state-feedback controller to place both system poles at -2.
   - Calculated the necessary feedback gains to achieve the desired stability and dynamic response.

3. **PID Controller Design:**
   - Utilized the Ziegler-Nichols tuning method to design and evaluate PID controllers.
   - Implemented the PID controllers in MATLAB, and analyzed their performance based on steady-state error and overshoot.

The project successfully implemented and tested control strategies using MATLAB, providing insights into system stabilization and controller design.
