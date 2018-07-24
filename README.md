# Praat-scripts-for-annotation
Open each script to see basic instructions for use, and attribution. These scripts come with no guarantee of functionality.

**add_tier.script** goes through a given directory, adding an interval tier to each textgrid.

**concatenate_files.script** exhaustively concatenates files in a given directory, with a user-specified silence in between. Handy for pairing up experimental stimuli. 

**concatenate_intervals.script** takes an annotated long sound object and concatenates labelled intervals, removing all non-labelled ones. Handy for removing silences from files. 

**delimit_silence.script** creates a textgrid for a long sound object, and places boundaries to delimit silences. Handy as a first step in segmenting a production task recording into component files.

**duplicate_tier.script** goes through a given directory, duplicating a given interval tier. 

**place_boundary.script** goes through a given directory, placing boundaries relative to existing ones on each textgrid. It doesn't create new tiers.

**save_intervals.script** takes an annotated long sound object and saves labelled intervals to separate sound files. 
 
**textgrid_create.script** goes through a given directory, bringing up each soundfile and for each creating a matching textgrid, automatically saving any changes you make to the textgrid. 

**textgrid_edit.script** goes through a given directory, bringing up each soundfile and associated textgrid, automatically saving any changes you make to the textgrid.

**textgrid_generate.script** goes through a directory creating a textgrid for each soundfile, without bringing files up for editing. 

**textgrid_view.script** goes through a given directory, bringing up each sound file and its associated textgrid. It doesn't save any changes you make to the textgrid. 
