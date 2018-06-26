# master-programs
Various programs I made during my master's in astrophysics.

All of the files work with the output of a modified version of the ISIS code, which itself is a modification of the RAMSES code. 
The output format is still the same so yt-project was the obvious choice for analysis.

This does not work perfectly with the standard version of yt since that changes the creation time parameter of the dark matter particles, making it impossible to distinguish them from the star particles. If for some reason you find yourself wanting to use this you have to make sure that you comment out the part of the yt-project that messes with that parameter.

Note also that this thing takes a lot of time, so unless you've got a machine with a lot of cores and memory you're going to be waiting a long time. Obviously the actual halo catalog is not present in this project, and neither is the simulation data since that would be problematic to put freely available online.

Some of these were also used to make the figures in the article that resulted from that work, found at https://arxiv.org/abs/1803.04197
