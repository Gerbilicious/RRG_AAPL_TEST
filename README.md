# RRG_AAPL_TEST
Relative Rotation Graph using historical AAPL data using Python
In this modified code, we add a label at the top of the plot that shows the AAPL ticker and the date range for the data set.

The start_date variable is assigned the first date in the data (data['Date'].iloc[0]), and the end_date variable is assigned the last date in the data (data['Date'].iloc[-1]).

We then use plt.text() to add the label at the top of the plot. The transform=plt.gca().transAxes argument ensures the text position is specified relative to the axes. The label is centered horizontally (ha='center') and vertically (va='center'), and we adjust the font size, weight, and the appearance of the bounding box.

The resulting graph will display the Relative Rotation Graph for AAPL, with the AAPL ticker and date range labeled at the top.
