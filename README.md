# Gestura
 
Creative Description:

	_Immersive Multisensory Art Experience with Music and Motion_
	
	This project is an immersive interactive experience that combines music, motion, and visuals to engage the user’s mind and senses. The idea originated from our shared passion for electronic components and music, leading us to create an installation where users can actively shape their own audio-visual experience. The heart of the project is **Max MSP**, a versatile tool that brings the entire experience to life by responding to body gestures captured through **Microsoft Kinect**.
	When no one is present, the installation runs in an idle mode, playing a generative audio track. As soon as someone steps into the interactive area, the project transitions to audio-visual mode, where users can influence both music and visuals through hand movements. By moving their hands horizontally and vertically, users can create melodies with instruments like the flute and violin or adjust effects on a synthesizer. At the same time, their movements shape a 3D visual representation of their silhouette, adjusting colors, shapes, and forms.
	Switching modes through simple gestures, users can seamlessly move from creating audio-visual art to playing a game inspired by **Pong**. In the game mode, players control a paddle with hand movements while responding to dynamic changes in speed, physics, and even camera angles. It’s a dynamic, immersive experience that blends the joy of creating with the challenge of gameplay.

Technical Description:

	_Interactive Audio-Visual Installation using Max MSP and Kinect_
	
	This interactive project leverages **Max MSP** and **Microsoft Kinect V1** to create an immersive audio-visual and gameplay experience. **Max MSP** serves as the core processing environment, utilizing Kinect to capture body gestures, which are translated into coordinates for controlling on-screen events.
	
	### Core Features:
	
	1. **Idle Mode and Audio-Visual Interaction**:
	    - The project remains in idle mode when no human skeleton is detected by the Kinect, playing a generative audio track.
	    - Once a user enters the designated space, the installation switches to interactive audio-visual mode, which includes three sub-modes controlled by hand movements (X & Y directions).
	    - The left hand manipulates musical notes (flute and violin), while the right hand adjusts synthesizer effects and visual parameters, such as silhouette color and form.

	2. **3D Visual Component**: 
	    - Visuals consist of a dynamic 3D particle system that traces the user’s silhouette. The right-hand controls the hue and shape of the particle display in modes two and three.
	
	3. **Game Mode**:
	    - The project incorporates a **Pong-inspired game** where the user controls the paddle via left-hand gestures, and the ball reacts to physical laws. Audio feedback is generated based on user interactions, enhancing the immersive experience.
	    - The game is a self-contained application developed exclusively in Max MSP only
	    - Game levels progressively increase in difficulty, altering ball speed, bounce rate, and camera rotation to introduce new challenges.
