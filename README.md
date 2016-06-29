Werl Engine
====
What is it?
----
It is planned that it will be a game engine with a seperate rendering and physics engine so that you can choose what you want to build and what you want to have done. It will incorperate [dglsl](https://github.com/icecocoa6/dglsl "dglsl"), [gl3n](https://github.com/Dav1dde/gl3n "gl3n"). It is bassed on the [meld](https://github.com/meld-3d/meld) engine by Alex Parker.

Windows compilation requires dmc, dmd and dub. OSX compilation requires gcc, dmd and dub. You will also need to have the glwt library available. To create a new project:

	dub init helloworld
	
Add Werl Engine to the project dependencies:
```d
	comming soon
```
	
Import and initialise meld in your main loop:

	import meld;

	void main()
	{
		Window window = new Window("Hello, world!", 640, 480);
		
		while (window.IsRunning())
		{
			window.Swap();
		}
	}
For it is still just meld with extra dependencies. That will change!
