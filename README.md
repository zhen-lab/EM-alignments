# EM-alignments


## Good tutorial
https://tube.switch.ch/videos/c3f982f2


## Pipeline
1) Make new TrakEM2 project.
2) Import images into project using a text file generated by `list_images_in_text_file.py`.
3) Adjust image filters to equalize background intensity.
4) Montage each section individually.
5) Align sections to eachother, linear then elastic.
6) Export images as tiles for CATMAID using `export_for_CATMAID.bsh`.
