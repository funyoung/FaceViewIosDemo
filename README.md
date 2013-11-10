FaceViewIosDemo
===============

A face view from open course demo

Course content: 44:10"
.Happiness
Shows a level of happiness graphically using a simley/frowny face
.Model
int happiness; // very simple Model
.View
Custom view called FaceView
.Controller
HappinessViewController
.Watch for ...
DrawRect: (including a drawing "subroutine" (push/pop context))
How FaceView delegates its data ownership to the Controller with a protocol
One gesture handled by Controller (Model change). the other byView (View change)

Extension later
.save view content to image file
.social share
