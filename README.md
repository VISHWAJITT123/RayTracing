# Ray Tracing

* Ray trace and draw a plane, some sphere objects, some cube objects
* Read in material properties of sphere and cube objects including:
	* Surface color
	* Emission color
	* Reflection coefficient( $k_a,k_d,k_{sp},sunshiness$ )
	* Image files for implementing texture mapping(only support *.bmp*)
	* Build-in texture (CHESS Board Texture)

## Including Files

* Project file *raytracing.xcodeproj*
* In raytracing file:
	* *bmpstruct.h* used to read *.bmp* files
	* *GLVector.h* creates a 3D vector data structure for convenience
	* *GLObject.h* creates :
		* Camera
		* Light Ray
		* Objects: Sphere,Plane,Cube,Model
	* *main.cpp* implements tracing and rendering, creates a scene and displays it.
	* *phofile_photo.bmp* a demo image texture

* In Result file:
	* screenshots of the demo scene
