# CalibrationCompensation
____________________________________________________________________________
There are 6 files (currently):
- MainWindow (the notebook with tabs corresponding to the tabbed files below)
- Home
- CreateFilter
- Playback
- CalibrateLRA
- DesignExperiment

____________________________________________________________________________
Each of the tabbed files follows the MVC (model-view-controller) structure:

Model:       Stores data (and methods to change data)
Controller:  middle-man between model and view
View:        UI

The model and the view do not interact with each other.
The controller interacts with both the model and the view.

Benefits to MVC:
- Easy to read and modify
- Differentiates between layers
- Minimizes duplicated code

INCREDIBLY helpful video about making tkinter gui using MCV structure
https://www.youtube.com/watch?v=EGn2MWK5MjU&list=PLCsFQ-aA6NyI959pgZL8LXbCTtzyD2Xpe&index=22
____________________________________________________________________________

