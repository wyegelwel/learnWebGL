learnWebGL
==========

First steps of learning webgl. 


I am following the tutorial: http://learningwebgl.com/blog/?page_id=1217 although most of my files don't match the suggested code as I played around quite a bit. 

You can see the crawlies demo at: http://cs.brown.edu/courses/cs123/demos/crawlies/crawlie_demo.html

Problems encountered
=========
See the file problemshad.txt for the full list.

Developing locally:

* Textures locally:
	If you get an error about Security Agent and illegal access it is likely that you are trying to read files locally which chrome isn't happy to do.
	To get around this, you need to add a flag for reading files locally.
	In windows:

  "C:\PathTo\Chrome.exe" –allow-file-access-from-files
