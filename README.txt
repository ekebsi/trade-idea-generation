1. Installation

	All necessary libraries are already installed with the Anaconda distribution.

2. Project Motivation

	The aim behind this project is to use CSV-files with stock data that are extracted from 
	any free online stock screener (NASDAQ, Yahoo, Zacks etc.) and go through a quantitative analysis
	to identify sectors/industries with highest earnings growth estimates and potential long/short trade ideas.

3. File Descriptions

	A package to convert read a CSV-file containing stock data to a pandas dataframe.

	The CSV-file must have a format identicale to the format of the example data to be found in file "zacks_stocks_custom_screen_2024-08-21.csv".
	The CSV-file must be on the same directory as the file "TradeIdeaGeneration.ipynb".

	Also do cleaning of the dataframe and sorting of the cleaned dataframe.

	Also identify the top 10 and bottom 10 industries with highest/lowest Earning Growth and output these as a plot.

	Also identify the potential Long stocks and short stocks.

	Also identify outliers which are stocks with either missing data or uncommon data (too high/ too low values).

	Finally, output an excel format file containing the follwing:

		- the cleaned full stock data set.
		- the identified outliers.
		- the identified potential long stocks.
		- the potential short stocks.

4. How To Interact With Your Project

	For details on how to interact with the project, please see the detailed comments and explanation provided within the file "TradeIdeaGeneration.ipynb".

5. Licensing, Authors, Acknowledgements
	
	None




