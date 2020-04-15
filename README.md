# Python-Pillow-on-iOS
Running Pillow/PIL on iOS is the headache for lots of developers, well, using python to develope a REAL applicaton on iOS is the challenge
task for many of us. This project is to put Python, Pillow/PIL together running on an Iphone and/or simulator. 

The project is based on the beeWare (rubicon and toga) fundation, and compiled pillow as static library, then use pure Python code to finish. 
The key functions are as following:

1. open iOS album to pick an image
2. The image will be first processed by PIL and displayed on the screen.
3. practise other PIL functions by choosing (b/w, enhance, edge-finding, blur or histogram), the image will be changed to see the result. 

1. Download all zip files and unzip them
2. open the helloword project in xcode
3. add the support files under helloword project
4. under project target, add the pillow static library accordingly (libpillowa-simu.a for simulator, libpillowa-iphone.a for iphone)
5. set build arch to x86_64 and arm64
6. build and run
7. enjoy!


BTW: if you are interested in pillow source code, I can upload them. however there are some serious code changes for pillow source code in order to successfully make the pillow static library working in iOS.   
