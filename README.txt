Albert Tan
Particle Filter SLAM

All work is documented in 5 notebooks

1. Lidar Processing.ipynb: Converts lidar points from lidar frame to world frame and displays first scan
2. Synchronize Sensor Data.ipynb: Synchronizes all sensor data (FOG and encoder) into the lidar timeframe 
3. Dead Reckoning Data.ipynb: Uses motion model to determine trajectory for dead reckoning 
4. Dead Reckoning Plot.ipynb: Plots the map and trajectory of dead-reckoning using the data of previous notebook 
5. SLAM Particle Filter.ipynb: Final SLAM notebook, adds update step and uses map correlations to localize and determine best particle, then projects scan at each time step





SLAM_Video_50_Particles.mov: video that shows full SLAM at each timestep in 3x speed 
