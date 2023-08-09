# OptiTrack Integration into 3D Slicer

This project is an Optical Tracking system using the OptiTrack camera hardware meant to be integrated into SlicerMorph (a [*3D Slicer*](https://download.slicer.org/) extension) and replicate the functionality of old school mechanical digitizing pens with the optical tracking of a digitizing stylus. The project uses the [*OptiTrack V120 Duo*](https://optitrack.com/cameras/v120-duo/) camera system  as well as the [*Motive*](https://optitrack.com/software/motive/) data processing software. 

# Second Milestone

## Summary

In this milestone, I managed to set up the OptiTrack V120 Duo tracking camera and get it working as well as get familiar with the Motive software's less complex user interface. Once the software was up and running, I created *Rigid Body Objects* for both the stylus and a temporary reference object to be able to visualize the test objects from the perspective view to get started. I then exported the profile from Motive (.xml file) and also created my configuration file (.xml file) to get started with the PLUS Server Launcher and establish the intermediary connection between the two softwares and begin sending data to 3D Slicer. 

## Challenges

At this point, I had faced a frustrating issue with launching the server via the PLUS Server Launcher and establishing the connection to be able to send data to 3D Slicer. Having both my configuration and profile (.xml) files in the same directory, I continued to receive errors from the PLUS Server Launcher as it failed to establish the connection. Eventually I discovered that the problem was due to the live data transfer to Slicer, and that the *"Broadcast Frame"* must be toggled on through Motive to be able to do live broadcasting. The *"Broadcast Frame"* toggle can be found in Motive under View > Data Streaming Pane > *Broadcast Frame*.  

## Next Steps 

In future efforts regarding the optical tracking project, I will first begin by sending **live data** over to 3D Slicer. This way, I can begin placing basic markers and lines over several trials to test the accuracy at which the instrument performs. With this measurement of accuracy, I can then determine whether or not this is a feasable method to approach research on 3D models. Additionally, I will include a more realistic model of the stylus itself for a better and more accurate visualization through Slicer. 

GIF

# First Milestone

## Summary

In this milestone, I worked on getting familiar with the 3D Slicer user interface (UI). Being a fairly complex software with a multitude of different modules, it is important that I first get familiar with the UI. I learned how to load sample data as well as custom data and install certain extensions which are crucial to this project (a few extensions include: **SlicerMorph**, SlicerIGT, and SlicerOpenIGTLink). Most importantly, I learned how to use the 'Markups' feature of 3D Slicer, which allows the user to add control points, connectors, and planes onto the model. This markup feature is crucial because it is very similar to what this final optical tracking project tries to replicate.

## Challenges

The main challenge I faced at this time was navigating the complexity of the 3D Slicer UI and discovering the function of the important features of Slicer. Some guidelines and tutorials that were useful to me in getting introduced to the Slicer UI and functions include the [*SlicerIGT tutorials*](https://www.slicerigt.org/wp/user-tutorial/) as well as the [*SlicerMorph tutorials*](https://github.com/SlicerMorph/Tutorials) in their documentation. SlicerMorph is more specific to my implementation, so most of their tutorials were slightly more relevant to my project. 

3D Slicer user interface example:

<img src="3DSlicerUI.png" width="1000" height="625" />

## Next Steps

In the following progression of this project, I will begin camera set up as well as download and start the Motive software to begin the first steps of this project. I will also install an intermediary between the tracking software (OptiTrack) and the vizualization software (Slicer); the [*PLUS Toolkit*](https://plustoolkit.github.io/) is the intermediary. 

