# Apex-Portal-Shader
Procedural portal shader, inspired by Wraith from Apex Legends


From your project file; 
File > Append > DG_Portal > NodeTree > DG_Portal

Add a plane and delete default shaders. Add new shader > DG_Portal

Controls and Initialization
Step 0: Color attributes chosen to match in-game model, but you may customize
Step 1: Set "FPS" attribute to project frame rate
Step 2: Adjust Emission according to scene
Step 3: Animating open/close portal
        - Visibility 0 = Portal closed
        - Visibility 1 = Portal open
        Set attribute key frames by hovering over "Visibility" and using "i" key
Step 4: Press play. The portal is animated by default but you may want to use "Speed" attribute to adujst to your liking
