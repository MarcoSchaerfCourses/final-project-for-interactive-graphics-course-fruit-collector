# final-project-for-interactive-graphics-course-fruit-collector
	
	In this project, we have created a fruit collector. This fruit collector is a robot manipulator that has three joints, an end-effector that collects the fruits, a base, and four wheels that help the robot move to the locations when needed. This robot’s task is to grab two different types of fruits, oranges and apples, that are located in different positions throughout three trees and drop them in the basket. The scene is set up in 3D with an interface to pick which fruit to collect as two buttons and the availability of movement of the angle perspective (camera) with the user’s mouse. During the collecting cycle, the interface shows a description of the steps occuring while in the scene the camera is panning in different angles in order to show all the different perspectives. 
	For the creation of this project, we used basic WebGL with the Three.js advanced library. WebGL is a Javascript API used for rendering interactive 2D and 3D graphics in a web browser. It is integrated into the standards of browsers, so the processing of the graphics are done using GPU from the browser making it faster to process graphics. As we worked through this project, we had to change browsers from Chrome to Firefox since Chrome does not allow the usage of local host files because of security issues. This means that the images used for the texture of the components were not appearing in Chrome, but since Firefox does not have such restrictions we started using this browser. 
	Three.js then uses the basic WebGL to provide a more advanced library which enables a faster, wider and simpler ways to create. When we started this project, we were using only basic WebGL and even though we went really far in the creation of the fruits and the robots we started realizing how long it would be taking us to create all the components for our scene so we looked for methods to create those faster and easier. That is when we ran into Three.js and after learning about the library and using it, we realized the improvement it would provide us. Three.js gave us the ability to create complex 3D animations without the burden of creating things from the basic level for WebGL. Some of the commands that were used and useful in our project were: SphereGeometry, MeshLambertMaterial, TextureLoader, Matrix4().makeTranslation, scene.add(), .position.set(), .rotate.x, among others. 
