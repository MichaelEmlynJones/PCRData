PCRData
=======

These are ten data files relating to dilution assays. 

We will shortly upload a pdf contining details of primers etc for each.

The format is designed to allow us to upload `unsanitized' data; that is, data that contains outliers. To this end the first 
column is currently a column of ones, indicating that the corresponding row is data that we believe can be routinely
analysed.  The files as they stand do not contain outliers. That's why there are usually three replicates, but occasionally
only two. We  will go back through the lab data and put back in the 
occasional sample that might have had a bubble or a fly in it,or which didn't seem to do anything. The first column 
for these will be a number other than a one. We will probably use some binary code to determine the `fault' or `faults'
leading us to rule a sample as an outlier.

The second column is the dilution, a 1 being undiluted, a 1024 being ten two-fold dilutions later etc. This is set up
so you don't have to add by hand the data relating to dilution. A program which analyses one file should analyse them all 
without any intervention.

Columns 3 et seq are the fluorescence, without baseline correction and without scale correcton.

Have fun.

Michael and others.
