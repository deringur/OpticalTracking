# OptiTrack Integration into 3D Slicer

This project is an Optical Tracking system using the OptiTrack camera hardware meant to be integrated into SlicerMorph (a [*3D Slicer*](https://download.slicer.org/) extension) and replicate the functionality of old school mechanical digitizing pens with the optical tracking of a digitizing stylus. The project uses the [*OptiTrack V120 Duo*](https://optitrack.com/cameras/v120-duo/) camera system  as well as the [*Motive*](https://optitrack.com/software/motive/) data processing software. 

# First Milestone

## Summary

In this milestone, I worked on getting familiar with the 3D Slicer user interface (UI). Being a fairly complex software with a multitude of different modules, it is important that I first get familiar with the UI. I learned how to load sample data as well as custom data and install certain extensions which are crucial to this project (a few extensions include: **SlicerMorph**, SlicerIGT, and SlicerOpenIGTLink). Most importantly, I learned how to use the 'Markups' feature of 3D Slicer, which allows the user to add control points, connectors, and planes onto the model. This markup feature is crucial because it is very similar to what this final optical tracking project tries to replicate.

## Challenges

The main challenge I faced at this time was navigating the complexity of the 3D Slicer UI and discovering the function of the important features of Slicer. Some guidelines and tutorials that were useful to me in getting introduced to the Slicer UI and functions include the [*SlicerIGT tutorials*](https://www.slicerigt.org/wp/user-tutorial/) as well as the [*SlicerMorph tutorials*](https://github.com/SlicerMorph/Tutorials) in their documentation. SlicerMorph is more specific to my implementation, so most of their tutorials were slightly more relevant to my project. 

3D Slicer user interface example:

![3D Slicer User Interface](IMG_6633.jpg){:height="33%" width="32%"}

## Next Steps

In the following progression of this project, I will begin camera set up as well as download and start the Motive software to begin the first steps of this project. I will also install an intermediary between the tracking software (OptiTrack) and the vizualization software (Slicer); the [*PLUS Toolkit*](https://plustoolkit.github.io/) is the intermediary. 
