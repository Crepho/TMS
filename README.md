# TMS
The triple modal signature dataset.
Triple Modal Signature (TMS) dataset
This is a handwritten Chinese signatures dataset including offline images, online sequences and hand videos. The TMS dataset consists of 50 writers, each contributing 10 multimodal genuine signatures and 10 people have additional 10 forgeries.
The TMS dataset consists of 50 writers, each contributing 10 multimodal genuine signatures and 10 people have additional 10 forgeries.
The dataset includes 60 subfiles (each for an individual writer) and a python file which processes the data. The name of forgery signature file starts with "F_". Each subfile includes 10 static images, 10 dynamic sequences and 10 videos.
(1) Images are in size of 1278×798 with RGBA channel, and stored in PNG format.
(2) Raw features of sequences include coordinate x and y, pressure p, time gap t (in milliseconds) and pen status s, composing the time sequence and stored in JSON format. The max horizontal and vertical coordinates are 1600 and 1000 respectively. The value s = 0, 1, 2 means pen-down, moving and pen-up respectively.
(3) Videos record the entire process of writing, stored in MP4 format with frame size of 640×480 and rate of 25 frames per second.

