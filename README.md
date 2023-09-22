# Galileo

In the future this will be a project which is focused at easing the collection of experimental data initally aimed at people using ROS (Robot Operating System).

### Ideas

- Allow the user to create experiments by defining a template of what data they want to collect, and what the variables are.
- Automatically start ROS bag recordings, OBS video recordings, audio recordings, etc. for each run of the experiment. 
- Store data in easily accessible processing formats like JSON, sqlite, etc.
- Allow the user to automatically duplicate the collected data to attached hard drives, S3-storage compatible clouds, etc.
- Allow event triggered data collection i.e. the value in a ROS message which is published changes and this should trigger e.g. a value to be recorded, or an image from a camera, or ROS topic to be stored seperately.
- Show a timeline, and allow the user to add nodes at specific timestamps.
- Visualise data, and provide simple analysis tools to aid the user in choosing which variable to vary next.
- Allow multi-user collaboration for collecting data. This could take the form of an app which can connect to the desktop version iff they are in the same network. The app could then be used to add measurements, phots taken by the smartphone, notes, etc. 
