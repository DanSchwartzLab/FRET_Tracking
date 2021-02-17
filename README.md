# FRET_Tracking
This software is used to analyze FRET trajectories of a donor diffusing in a dense anisotropic film deposited on a plane of randomly place acceptor for the purpose of characterizing the transport properties normal to the surface. Full details, derivations, and instructions can be found in the manuscript entitled "Single molecule characterization of anomalous transport in a thin, anisotropic film" and corresponding supplemental material published in Analytica Chemica Acta, and detailed descriptions of the inputs and outputs can be found in the included .m files. The FRET data is organized such that each row contains a time trace of each trajectory and the columns correspond to different frames.  Example.mat is a demo and includes all parameters and data necessary to run the full analysis. Also included are the results of running each of the included functions. The software has been tested with Matlab 2019a, and requires the global optimization toolbox. The Parallel computing toolbox is also recommended for shorter run times. 
