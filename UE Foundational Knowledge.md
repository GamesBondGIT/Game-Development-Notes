
- ### [Default UE5 Interface](https://docs.unrealengine.com/5.1/en-US/unreal-editor-interface/)
	- ![[Pasted image 21235507190153.png]]
		1. Menu Bar
		2. Main Toolbar
		3. Level Viewport
		4. Content Browser
		5. Bottom Toolbar
		6. Outliner
		7. Details

- ### [UE Terminology](https://docs.unrealengine.com/5.1/en-US/unreal-engine-terminology)
	- **Project**
		- Every Basic Project has following folders
		- ![[Pasted image 25963432190153.png]]
		- And more folders like Plugins, Source, etc. also added later depending on the features of your project
	- **Blueprint**
		- Visual Scripting System for UE that uses node-based interface to create gameplay elements from within UE Editor
		- It uses object-oriented(OO) classes or objects in the engine
	- **Object**
		- Objects are the most basic class in Unreal Engine
		- They act like building blocks and contain a lot of the essential functionality for your Assets. Almost everything in Unreal Engine inherits (or gets some functionality) from an Object
		- In **C++**, <u>UObject</u> is the base class of all objects; it implements features such as garbage collections, metadata (<u>UProperty</u>) support for exposing variables to the Unreal Editor, and serialization for loading and saving
		- To know this more detail, we need to understand [**UE Architecture**](https://docs.unrealengine.com/5.1/en-US/programming-in-the-unreal-engine-architecture/)
	- **Class**
		- Class defines the behaviors and properties of a particular Actor or Object in Unreal Engine
		- Classes are hierarchical, meaning a <u>Class inherits information from its parent Class</u> and passes that information to its children
		- Classes can be created in C++ code or in Blueprints
		- Examples of Classes in UE are [Blueprint Class](https://docs.unrealengine.com/5.1/en-US/blueprint-class-assets-in-unreal-engine/), [Gameplay Classes](https://docs.unrealengine.com/5.1/en-US/gameplay-classes-in-unreal-engine/), etc.
		- Basics of [Creating Class](https://docs.unrealengine.com/5.1/en-US/class-creation-basics-in-unreal-engine/) in UE using Blueprint / C++ / Both
	- **Actor**
		- An Actor is any object that can be placed into a level, such as a Camera, static mesh, or player start location
		- Actors support 3D transformations such as translation, rotation, and scaling
		- They can be created (spawned) and destroyed through gameplay code (C++ or Blueprints)
		- In C++, <u>AActor</u> is base class of all Actors
		- More info :
			- [The basic gameplay elements, Actors and Objects](https://docs.unrealengine.com/5.1/en-US/actors-in-unreal-engine/) 
			- [Defines Actors and describes how to use them in level design. Also includes a rundown of the most common types of Actors.](https://docs.unrealengine.com/5.1/en-US/actors-and-geometry-in-unreal-engine/)
	- **Casting**
		- its important to Understand this
		- Casting is an action that takes an Actor of a specific class and tries to treat it as if it were of a different class
		- Casting can succeed or fail. If casting succeeds, you can then access class-specific functionality on the Actor you cast to
		- [Example](https://docs.unrealengine.com/5.1/en-US/unreal-engine-terminology/#casting)
		- **NOT THIS** - Casting is <u>different</u> from simply checking whether an Actor is of a given class, Checking an Actor is of a given class would simply return a binary (yes or no) answer, but wouldn't allow you to interact with any specific functionality of that class.
	- **Component**
		- A [Component](https://docs.unrealengine.com/5.1/en-US/unreal-engine-terminology/#component) is a piece of functionality that can be added to an Actor
	- 