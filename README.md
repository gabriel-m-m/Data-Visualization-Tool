# Publication Infographic Generator 
### General Information

This application takes a spreadsheet of publication data, in which each entry contains a list of author names, and generates a network graph. The nodes of the graph represent individual authors and the thickness of the edges correspond to the number of publications with shared authorship. Instances of this can be seen in the examples folder, which contains example outputs using real data (with names and other information redacted for privacy). The pandas library was used to convert the excel spreadsheet to a dataframe in python and manipulate the data, the NetworkX library was used to generate the graph, and the Bokeh library was used to make an interactive plot and allow the visualization to be saved as a png. The numpy library was also used for mathematical functions, and matplotlib for colour verification. 

### Instructions

To start the program run the whole notebook/all cells. Upon doing so you will prompted to input the filepath of your chosen .xlsx dataset. After choosing your file, you will also be able to enter the colour of the nodes and edges. Once you are finished, the graph will be generated and you will be taken to a new window. Here you can adjust the framing and sizing of the plot, and you have the ability to save the plot as a png.
