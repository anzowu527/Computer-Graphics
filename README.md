# Computer Graphic Project: Reproduce Flight Path
- We were provided with several video clips of airplane scenes from the course, from which we were to select one to recreate using Blender.
- I selected a clip featuring an airplane accelerating along a runway before taking off at a steep angle, nearly vertical, and executing a 360-degree rotation. The aircraft then performed various aerial maneuvers between takeoff and landing phases. Unfortunately, I can no longer locate the original video, but my description closely captures its content.
- The original video featured a change in camera perspective midway through, and my rendition similarly incorporates multiple camera setups to capture the scene.
- We need to design our own plane, runway, the entire environment, and scrip the motion.

## Files in the Repository
### Videos: Screen Recording of the scene from Blender Panel
- '_CameraA_pilot_perspective.mp4_': Camera A is mounted on the plane and perceives the pilot point of view
- '_CameraB_RunwayCam.mov_': Camera B is positioned at one end of the runway and is designed to capture the entire motion of the plane. Its lens will track the plane, ensuring it remains centered in the frame throughout.
- '_CameraC_Midway.mov_': Camera C is strategically placed to record the plane's movement from a unique angle at a specific moment. The footage it captures replicates a segment of the original video.
- '_CameraD_plane360rotation.mov_': This camera activates upon detecting the plane and continues tracking it through its rotation maneuver immediately following takeoff.
- '_Render.avi_': This is a super short Rendered video of several frame. It took a very long time to render the entire motion because of various reasons: the object, texture... that I put in the scene.
### pdf
- '_Plane Paper.pdf_': Includes the research I was focusing on for this project, relevant properties and objects of Blender, my experimental activity and products, and Blender-specific implementation.
- '_Render test.pdf_': I estimated the total time it will take to render the view from each of the camera.
### .py
- '_flight-path.py_': A python script that scripts that plane motion.

## Check out my work
1. Make sure you have Blender installed
2. Download the Plane.blend from the repository
3. Import it to the Blender
4. Choose the camera point of view you want be in
5. Click the start button to start the motion
