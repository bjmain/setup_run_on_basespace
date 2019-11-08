## Set up run on BaseSpace 
https://basespace.illumina.com/dashboard
Prep tab - upload CSV with samples
Biological samples - sample import template.
SampleID and Name have to be different.
NOTE: BaseSpace does not allow prepping more than 96 samples so you can only upload 96 and then you need to manually demultiplex. (Boo Illumina)
My example: NOTE: You need to leave species blank because BaseSpace is dumb and doesn’t recognise mosquito species.
So just click a few samples and and click prep libraries. We’ll demultiplex offline anyway.
https://www.dropbox.com/s/9sulp6w6s6vet9m/basespaceTemplate_bakeoff.csv?dl=0
	
Libraries
Select IDT-ILMN Nextera UD Index Set A (this is required to allow 10bp index reads) and then Auto Prep. Nextera DNA if you only want 8bp index.
I made up a name for plate ID
Click the plate and then click pool libraries.
Drag some of the blue dots to the sample tube (again we will multiplex later) and name the pool.
Pools
Click pool ID and then Plan Run
Planned Runs
MiniSeq, Name it, Paired-end 149, 
