# ERC-MBRL-Gazebo-Map

NOTE (22/07/2026) : The current map is only the basic layout but will help in conducting Robotis simulation for Nav2. I am still working on adding the models and will be done this weekend.

Instructions
1. Download the 'mbr_library.sdf'.
2. Within your ros2 workspace, create a folder named 'worlds'. It is important you create a separate directory to keep things organised as later on the file structure will look as such:

    worlds/
   
    ├── mbr_library.config
   
    ├── mbr_library.sdf
   
    └── meshes/
   
        └── plant.glb
   
        └── desk.glb
   
        └── bookshelf.glb
   
        └── chair.glb
   
   ...
   
4. Open terminal, change the exact directory in your ros2 workspace where 'mbr_library.sdf' is located.
5. Run the command 'gz sim mbr_library.sdf'
6. Your gazebo will open showing the library map :)
<img width="1854" height="1048" alt="Screenshot from 2026-07-22 22-49-28" src="https://github.com/user-attachments/assets/fbc7a323-5c6c-45b0-a4c1-c6f5da2de43b" />


