# Homegeneity-test-for-hydrologic-time-series
Buishand and Double Mass tests for hydrologic Time serie homogeneity

- The data should be stored in an excel file (numeric year in one column, and time series in others columns with header row for the name). Blank cell for missing values
- Specify the name / path of the exel file, and sheet of the data (e.g. sheet_name="Data")
- Specify the number of rows to skip before the header row (e.g. skiprows=range(0, 1) to skip row 1)
- Specify the column numbers to use (starting from 0), including the year column (e.g. usecols=[1, 2, 3, 4, 5]) for columns 2 to 6).

TIPS: 
- The dynamic graphs can be saved to disk by hand with the interactif menu above the plot
- The fig.write_image('data.png') method in the code can be enabled in order to generate the graph file automaticaly. Unfortunatly this method needs the installation of plotly-orca utility with the help of psutil by the command line: conda install -c plotly plotly-orca == 1.2.1 psutil request
- Run the notebook preferably under Jupyter in order to display "dynamic graphs" (note Jupyter Lab which needs a optionnal extension to display "dynamic graphs"). There is no problem for static graphs.
- Alternately, you cans disable plotting lines of the cell below, and replace them by the 2 lines wich are currently disable (there is no alternate solution for Double Mass test)

<img src= "https://github.com/loicduffar/Homegeneity-test-for-hydrologic-time-series/blob/master/out/Buishand%20test%20Result.png" width="50%"></img>
<img src= "https://github.com/loicduffar/Homegeneity-test-for-hydrologic-time-series/blob/master/out/Double%20mass%20Graph.png" width="50%"></img>
