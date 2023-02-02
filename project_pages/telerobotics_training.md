## Telerobotics training

### Summary

As discussed [here](https://WrenmcQueary.github.io/project_pages/teleoperated_rescue_robot), I'm currently collaborating with the DCXR Lab of Dr. Craig Yu at George Mason University, as well as the SubT Lab of Dr. Nick Wang at NYCU in Hsinchu, Taiwan, to build a robot for use in search-and-rescue missions.  The robot is piloted remotely, and is designed to facilitate spatial interpretation of sounds, to assist its pilot in locating calls for help and other critical sounds with high accuracy.

To provide the pilot with rapid, easy, and effective field training, I am pair-programming with another researcher to develop a training simulation, which will provide the pilot with missions completed by a virtual simulacrum of the robot in Unity and Gazebo.  This allows more pilots than robots to train at once, protects real robots from damage during training, and eliminates the need for a painstakingly orchestrated real training environment.

In the virtual environment, realistic acoustics are paramount, due to the importance of sound in a real search-and-rescue mission.  To this end, we have engineered our training simulation to provide realistic propagation of stereo sound, including material-attentive occlusion and reflection.  After importing the geometry for an environment (acquired via photogrammetry) into Unity, we overlay each acoustically significant object with an invisible double.  Each object's double contains information on its material and other acoustic properties, allowing it to realistically influence the acoustics of the space.

See below for an image of one of our environments, along with another image in which the invisible acoustic doubles are revealed.

![Medical center room no occluders](/images/projects/telerobotics_training/medical_center_room_no_occluders.png)

### Skills gained

By engineering realistic acoustics for our training simulations, I learned how to use industry-standard acoustic tools such as Resonance and FMOD.

![Medical center room with occluders](/images/projects/telerobotics_training/medical_center_room_with_occluders.png)
