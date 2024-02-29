# Computer Graphic Project: Reproduce Flight Path
<img src="https://github.com/anzowu527/Computer-Graphics/assets/77874807/97883e47-8fe9-4639-8169-70830b83582e" width="450">

<img src="https://github.com/anzowu527/Computer-Graphics/assets/77874807/391b00f1-7afb-40ca-b80a-d89495e99cf4" width="450" height='290'>

<img src="https://github.com/anzowu527/Computer-Graphics/assets/77874807/4b175aaa-d2e9-4bf0-bf40-b6f0ede4dd7a" width="450">

<img src="https://github.com/anzowu527/Computer-Graphics/assets/77874807/e4220dd6-deef-40aa-8206-6e4de644a8c0" width="450">

- We were provided with several video clips of airplane scenes from the course, from which we were to select one to recreate using Blender.
- I selected a clip featuring an airplane accelerating along a runway before taking off at a steep angle, nearly vertical, and executing a 360-degree rotation. The aircraft then performed various aerial maneuvers between takeoff and landing phases. Unfortunately, I can no longer locate the original video, but my description closely captures its content.
- The original video featured a change in camera perspective midway through, and my rendition similarly incorporates multiple camera setups to capture the scene.
- We need to design our own plane, runway, the entire environment, and scrip the motion.

## Files in the Repository
### Videos: Screen Recording of the scene from Blender Panel
- '_**CameraA_pilot_perspective.mp4**_': Camera A is mounted on the plane and perceives the pilot point of view
- '_**CameraB_RunwayCam.mov**_': Camera B is positioned at one end of the runway and is designed to capture the entire motion of the plane. Its lens will track the plane, ensuring it remains centered in the frame throughout.
- '_**CameraC_Midway.mov**_': Camera C is strategically placed to record the plane's movement from a unique angle at a specific moment. The footage it captures replicates a segment of the original video.
- '_**CameraD_plane360rotation.mov**_': This camera activates upon detecting the plane and continues tracking it through its rotation maneuver immediately following takeoff.
- '_**Render.avi**_': This is a super short Rendered video of several frame. It took a very long time to render the entire motion because of various reasons: the object, texture... that I put in the scene.
### pdf
- '_**Plane Paper.pdf**_': Includes the research I was focusing on for this project, relevant properties and objects of Blender, my experimental activity and products, and Blender-specific implementation.
- '_**Render test.pdf**_': I estimated the total time it will take to render the view from each of the camera.
### .py
- '_**flight-path.py**_': A python script that scripts that plane motion.

## Check out my work
1. Make sure you have Blender installed
2. Download the Plane.blend from the repository
3. Import it to the Blender
4. Choose the camera point of view you want be in
5. Click the start button to start the motion
