# DARWIN-Dataset
Alzheimer's Disease Detection Using DARWIN Dataset

The DARWIN dataset contains handwriting data collected according to the acquisition protocol described in [1], which is composed of 25 handwriting tasks. The protocol  was specifically designed for the early detection of Alzheimer’s disease (AD). The dataset includes data from 174 participants (89 AD patients and 85 healthy people).
The file “DARWIN.csv” contains the acquired data. The file consists of one row for each participant plus an additional header row. The first row is the header row, the next 89 rows collect patients data, whereas the remaining 84 rows collect information from healthy people.
The file consists of 452 columns. The first column shows participants' identifiers, whereas the last column shows the class to which each participant belongs.  This value can be equal to  'P' (Patient) or 'H' (Healthy).
The remaining columns report the features extracted from a specific task. The tasks performed are 25, and for each task 18 features have been extracted. The column will be identified by the name of the features followed by a numeric identifier representing the task the feature is extracted. E.g., the column with the header "total_time8" collects the values for the "total time" feature extracted from task #8.
Benchmark performances achieved on the DARWIN dataset  have been published in [2].

