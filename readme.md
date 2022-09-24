First, I transposed the columns in excel before importing the file into Python. Then I used the pandas melt function to "unpivot" the table, which is turning the table from a wide-format into a long-format which is better for analysis. 
I want to find out how many people responded per question, also want to analyse how many people responded with the same answer per question. Also want to show the original question beside the answer.
I used the apply function, pd.renames, multi-level indexes, merges, used loc on multi-indexes and did some other pretty cool stuff.
In the end, fun :-) 