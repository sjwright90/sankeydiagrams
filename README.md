# sankey-diagrams
Make a sankey diagram


'''This file contains a series of functions used to transform and manipulate a csv or xlsx file into
a format appropriate for drawing a Sankey diagram and then producing said sankey diagram.
The tabular data does already need to be in a specific format. Each column should represent 
one event (in this case a given class offered in a given year). Each row will be an individual 
path through said events (in this case the grades a student got in a given class). Each cell 
contains the given result of the individual and that event (for example a "B" in "Calc1_2020"). 
The functions were built assuming string data would be the input, but I think numerical data 
would work. The intent of this work was to make a Sankey plot to track how students flowed 
through a series of college courses, the data set provided as an example is just randomly 
generated data, but shows how the process works. I believe the code should be highly adaptable 
to any instance where one is trying to make a sankey plot of categorical data, again some 
formating of your data set might be needed before it will work though.'''