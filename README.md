# photon-counting-lidar-data-processing-and-analysis
This is an preliminary processing and analysis for photon-counting lidar data.

# data

A sample data of SIMPL could be downloaded as below. Cope it and paste it on the browser.

https://icesat-2.gsfc.nasa.gov/legacy-data/simpl/data/maypop3/R5/grans/017_20150813/1404/simpl_l2a_20150813t142217_005_1.h5

# reader
main script used to read in batch: SIMPL_reader_batch_20190517.m

auxiliary function: time2distance.m

plot script: plotter_20190517.m

# usage
Put the readers and the sample data in the same directory, then run the SIMPL_reader_batch_20190517.m, and plot the output data using plotter_20190517.m. 
