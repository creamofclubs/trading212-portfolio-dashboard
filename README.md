# Trading <span style="color:SteelBlue"> 212 </span> portfolio tracker

After cloning the repository, navigate to it on a terminal and use command `streamlit run src/dashboard.py` to run the program in a browser.

Follow the instructions on screen to obtain your trading 212 API key, paste it in the text box and press enter. 

The process of obtaining the data will only take several seconds for fairly 'new' accounts but may take an extra multiple of 61 seconds, depending on the amount of data, for accounts with more activity, i.e more dividend payments received. (For most users this will be just 1 times 61 seconds)

The resulting dashboard will look something like this example:

![Dashboard](/images/example_dashboard_part1.png)

Further down other graphs about the positions in the portfolio and the received dividends will be visible:

![Dashboard](/images/example_dashboard_part2.png)
![Dashboard](/images/example_dashboard_part3.png)
![Dashboard](/images/example_dashboard_part4.png)

This last graph is interactive and any position that is held in the portfolio can be added in the textbox to view its dividend payout history.

To zoom in on a graph, hover over it and a symbol on the right side of the graph will apear. Click it.

All data can be downloaded (as a csv file) by navigating to the data tab, hovering over the dataframe and clicking the download icon that will appear on top of the dataframe.

By Rune De Neve
