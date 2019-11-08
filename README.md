## Set up run on BaseSpace 
https://basespace.illumina.com/dashboard
### Prep tab - upload CSV with samples
### Biological samples - sample import template.
#### SampleID and Name have to be different.
##### NOTE: If using UDI's, select which UDI Set (A,B,C, or D) and repeat (only allows 96 samples at a time). Then pool them in the next window.
##### Advanced note: Before you prepare libraries, set up the run on BaseSpace. Then generate your index scheme according to the auto_fill.
##### You need to leave species blank because BaseSpace doesn’t recognise mosquito species.
##### In most cases, I am just going to demultiplex offline, so I just click a few samples and and click prep libraries. (it would be nice if there was an option to just click demultiplex offline to avoid this game)
	
### Libraries
#### Select IDT-ILMN Nextera UD Index Set A (this is required to allow 10bp index reads) and then Auto Prep. Nextera DNA if you only want 8bp index.
#### I made up a name for plate ID
#### Click the plate and then click pool libraries.
#### Drag some of the blue dots to the sample tube (again we will multiplex later) and name the pool.
### Pools
#### Click pool ID and then Plan Run
### Planned Runs
#### MiniSeq, Name it, Paired-end 149, 
