# Assignment01 WriteUp - Erika Wood

Assignment01 WriteUp - Erika Wood

Download link for Game zip: https://github.com/sunny-erika/EngineeringII_Gamezips_Writeups/raw/9d813249ad2128cc39d50ae55f13494980c7cc59/MyGame_.zip

Download link for Game exe: https://github.com/sunny-erika/EngineeringII_Gamezips_Writeups/raw/main/ReleaseX64MyGame.gif

Download link for full WriteUp: https://github.com/sunny-erika/EngineeringII_Gamezips_Writeups/raw/main/WriteUp_compressed.pdf

WriteUp Summary:

•	Summary of issues I encountered and solutions I found

    - I excluded all files in the Direct3D filter instead of just the Graphics.cpp.
    - Linking errors 	Joshua suggested to delete the entire solution and recreated it.
    - 1 Link error remained	I forgot to add the OpenGLExtension reference after setting up the solution again 
    - How to get a CADE website set up	I found the place where to put the index.html in the Windows Explorer
    - However, rather than refreshing HTML I decided to use GitHub for submission
    - I accidentally also changed the name of the standard.shader in the Vertex path in the cpp file, so I changed it back to standard 😊 

•	Things I noticed
    A log file in the x64 but none in the x86.
    But once I got the game running both configurations contained log files 😊

•	What I researched/what I was confused about
  - I was not sure where to apply the sin function to receive an oscillating value over time.
    I first thought the variable needs to be set somewhere. Then I googled programming D3D and OpenGL and learned that they use different languages and looked at     
    coding examples. That gave me a clue about where to put the timing variable to have the changing color effect.
  - Changing the icon – I wasn’t sure at first which icon this will apply to – in the Windows explorer, the task list or the game window.
  - I simply tried it out and observed the change 😊
  - RGB color palette	https://www.tug.org/pracjourn/2007-4/walden/color.pdf
  - How to create a GIF from a video	https://www.adobe.com/express/feature/video/video-to-gif (does not support MKV file)

Even though I don’t have any previous experience with Game Engines, from a Software Engineering perspective I really like that the code is not just simply put into one project with different classes but the functionality is separated into different projects each serving a different purpose. I prefer that to putting everything into one project and organizing it with filters. That way other projects can simply choose which Engine project they need to add as a reference. 
I also feel that the coding style is very organized with plenty of comments and explanations. It is easily readable and there is a consistent naming convention throughout the projects. 
I really do appreciate the guidance we received with the step-by-step instructions on how to get the project set up. Thank you!!!

