# Create a new environment
Step 1 : open your anaconda prompt (for windows user search inside start menu )
                                   (for Ubuntu and Mac user you can open your terminal)

Step 2 : Create a new environment
                command : conda create -n facerecognition python==3.6.9
Step 3 : activate your environment
                conda activate facerecognition
Step 4 : Install requirements.txt in the newly created environment

Step 5 : Extra Command to run:
```
        conda install -c anaconda mxnet
        conda install -c conda-forge dlib
        pip uninstall numpy
        pip uninstall numpy
        pip install numpy==1.16.1
```

Step 6 : Installation and setup is done:
         a).  cd src
         b). python app.py

         Yor are good to go!!