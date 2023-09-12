# Pymaceuticals

Description: Complete data from a recent animal study is saved in the "data" folder within this repo. In this study, 249 mice who were identified with SCC tumors received treatment with a range of drug regimens. Over the course of 45 days, tumor development was observed and measured. The purpose of this study was to compare the performance of Pymaceuticals’ drug of interest, Capomulin, against the other treatment regimens.

Tables and figures were generated to help analyse the data, and a high-level summary was written to help executives analyse the data.

**Data analysis worked as follows:**
      
    The datasets are merged into a single DataFrame.
    Each duplicate mice is found based on the Mouse ID and Timepoint.
    A clean DataFrame is created with the dropped duplicate mice.
    The number of mice are shown from the clean DataFrame.
    The mean, median, variance, standard deviation and SEM of the tumor volume for each regimen is calculated using groupby.
    A new DataFrame is created with using the summary statistics.
    A bar plot showing the total number of timepoints for all mice tested for each drug regimen is generated using pandas and matplotlib.
    A pie plot showing the distribution of female versus male mice is generated using pandas and matplotlib. (3 points)
    A DatFrame that has the last timepoint for each mouse ID is created using groupby.
    The four treatment groups, Capomulin, Ramicane, Infubinol, and Ceftamin are assesed.
    A for loop is used to display the interquartile range (IQR) and the outliers for each treatment group.
    A box plot is generated that shows the distribution of the final tumor volume for all the mice in each treatment group.
    A line plot is generated that shows the tumor volume vs. time point for one mouse treated with Capomulin.
    A scatter plot is generated that shows average tumor volume vs. mouse weight for the Capomulin regimen.
    The correlation coefficient and linear regression model are calculated for mouse weight and average tumor volume for the Capomulin regimen. (10 points)
    
How to run: Ensure you have downloaded the repository first, then load Jupyter Notebook within that downloaded folder using your Terminal. Run each cell starting from the top to obtain the data you require.
