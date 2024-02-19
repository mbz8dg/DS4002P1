</head><body class="c14 doc-content"><h1 class="c6 c8" id="h.pppg67o7zrtn"><span class="c17">DS4002P1</span></h1><h2 class="c15 c6" id="h.6wziwiic7ds7"><span class="c11">Section 1: Software and platform section</span></h2><p class="c0"><span class="c1">For this project we used tools including Rstudio and Python. Rsutdio was used for a variety of data processing purposes. First, Rstudio was used for data processing including appending columns such as percent change in price for later analysis. Rstudio was once again used to retrieve sentiment and append scores using the VADER package. Finally, Rstudio was used to run the final regression and GGplot2 was used to visualize. Rstudio for Windows was used for regression and visualization, and all other processes were run on MacOS. Python was used to obtain date data from the URL using regex.</span></p><h2 class="c6 c10" id="h.bnjye6d627wl"><span class="c11"></span></h2><h2 class="c15 c6" id="h.qtojbk4kjjfx"><span class="c11">Section 2: A Map of your documentation.</span></h2><p class="c0"><span class="c1">&#9500;&#9472;&#9472; DATA</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; LCID Stock Trends .gsheet</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; LCID_Stock_Trends.csv</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; LCID_initial_raw_query.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; LCID_updated_with_date.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; NVDA_Stock_Trends.csv</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; NVDA_initial_raw_query.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; NVDA_with_dates.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; Sentiment_score.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; daily_stock_percent_changes.csv</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; lcid_stock_data_sentimentVpercChange.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; nvda_stock_data_sentimentVpercChange.xlsx</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; Data Appendix.pdf</span></p><p class="c0"><span class="c1">&#9500;&#9472;&#9472; OUTPUT</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; Analysis_plan_final.png</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; Compound_Sentiment_Score.png</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; regression_results.png</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; Sentiment_by_date.png</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; Stock_Information_Comparison.png</span></p><p class="c0"><span class="c1">&#9500;&#9472;&#9472; SCRIPTS</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9500;&#9472;&#9472; R</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9474; &nbsp; &#9500;&#9472;&#9472; R.Rproj</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9474; &nbsp; &#9500;&#9472;&#9472; correlationLm.R</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9474; &nbsp; &#9500;&#9472;&#9472; desktop.ini</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9474; &nbsp; &#9500;&#9472;&#9472; lcid_stock_data.csv</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9474; &nbsp; &#9500;&#9472;&#9472; mergingdailypercents.Rmd</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9474; &nbsp; &#9492;&#9472;&#9472; nvda_stock_data.csv</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &#9492;&#9472;&#9472; rawDataProcess</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &nbsp; &nbsp; &#9500;&#9472;&#9472; extractDatesFromUrl.py</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &nbsp; &nbsp; &#9500;&#9472;&#9472; sentimentVsScoreClean.py</span></p><p class="c0"><span class="c1">&#9474; &nbsp; &nbsp; &nbsp; &#9492;&#9472;&#9472; sentiment_score.Rmd</span></p><p class="c0 c5"><span class="c1"></span></p><p class="c0 c5"><span class="c1"></span></p><p class="c0"><span class="c1">&nbsp; </span></p><h2 class="c6 c15" id="h.mnrhlzab52z1"><span class="c11">Section 3: Instructions for reproducing your results. </span></h2><p class="c0"><span class="c20">This will need to be updated once we have final file names, and Master Scripts file to make sure the order is correct.</span></p><p class="c0"><span class="c1">This project takes 4 base data files and performs sentiment analysis and linear regression to achieve the given results.</span></p><h3 class="c0 c6" id="h.sr9upyonndwz"><span class="c16">Raw data collection:</span></h3><p class="c18"><span class="c2">NVDA_initial_raw_query.xlsx</span><span>: original raw data query from databar.ai. Link to data:</span><span class="c4"><a class="c9" href="https://www.google.com/url?q=https://databar.ai/public-table-full/9419fc15-9bd5-4050-9253-155b4dc56111&amp;sa=D&amp;source=editors&amp;ust=1708366143322583&amp;usg=AOvVaw3sUFMFCUUumf61CtCDhHgj">https://databar.ai/public-table-full/9419fc15-9bd5-4050-9253-155b4dc56111</a></span></p><p class="c18"><span class="c2">LCID_initial_raw_query.xlsx</span><span>: original raw data query from databar.ai. Link to data:</span><span class="c4"><a class="c9" href="https://www.google.com/url?q=https://databar.ai/public-table-full/361fe669-c6b6-4f89-b7cc-9561d7bc2314&amp;sa=D&amp;source=editors&amp;ust=1708366143323013&amp;usg=AOvVaw1FrLabgWHbc4iFaCtBvpv0">https://databar.ai/public-table-full/361fe669-c6b6-4f89-b7cc-9561d7bc2314</a></span></p><h3 class="c19 c6 c21" id="h.vegrs7ug7ybu"><span class="c16">Data processing:</span></h3><ul class="c7 lst-kix_m0a7idvf7f6d-0 start"><li class="c13 li-bullet-0"><span>To extract Date info from the raw data, run </span><span class="c2">extractDatesFromUrl.py</span><span>&nbsp;on </span><span class="c2">NVDA_initial_raw_query.xlsx </span><span>and </span><span class="c2 c12">LCID_initial_raw_query.xlsx</span></li></ul><ul class="c7 lst-kix_m0a7idvf7f6d-1 start"><li class="c3 li-bullet-0"><span>The result files are </span><span class="c2">NVDA_with_dates.xlsx</span><span>&nbsp;and </span><span class="c2">LCID_with_dates.xlsx</span></li></ul><ul class="c7 lst-kix_m0a7idvf7f6d-0"><li class="c13 li-bullet-0"><span>To combine sentiment scores and daily percentage change by the same date for each data, run </span><span class="c2">sentimentVsScoreClean.py</span><span>&nbsp;on </span><span class="c2">NVDA_with_dates.xlsx</span><span>&nbsp;and </span><span class="c2">LCID_with_dates.xlsx</span></li></ul><ul class="c7 lst-kix_m0a7idvf7f6d-1 start"><li class="c3 li-bullet-0"><span>The result files are </span><span class="c2">nvda_stock_data_sentimentVpercChange.xlsx</span><span>&nbsp;and </span><span class="c2">lcid_stock_data_sentimentVpercChange.xlsx</span></li></ul><p class="c0"><span>First, take the base data files </span><span class="c2">NVDA.xlsx</span><span>&nbsp;and </span><span class="c2">LCID.xlsx</span><span>. Running the extractDatesFromUrl.py code file will pull date data for each sentiment from the URL&#39;s which will be important for merging later on. The result datasets with date are stored in data folder, called </span><span class="c2">LCID_updated_with_date.xlsx </span><span>and </span><span class="c2">NVDA_with_date.xlsx</span><span>.</span></p><p class="c0"><span>Second, run the </span><span class="c2">sentiment_score.Rmd</span><span>&nbsp;file in Rstudio to append the VADER compound sentiment scores to the text data, and combined the NVDA sentiment score with LCID sentiment score by published date. The result file is named as </span><span class="c2">Sentiment_score.xlsx</span><span class="c1">.</span></p><p class="c0"><span class="c2">NVDA_Stock_Trends.csv </span><span>and </span><span class="c2">LCID_Stock_Trends.csv</span><span>&nbsp;must be cleaned to create </span><span class="c2">daily_stock_percent_changes.csv</span><span>. Their data types must be converted to reflect date and integer data types in order to run analysis. Then, the daily percent price change is found for each stock by subtracting the opening value from the closing value, dividing it by the opening value, and multiplying that value by 100. The daily stock percent change is made into a column, and the two sets are merged on date. Finally, the merged data set is exported as </span><span class="c2">daily_stock_percent_changes.csv</span><span class="c1">. &nbsp; &nbsp; &nbsp; &nbsp; </span></p><h3 class="c0 c6" id="h.ydf3wci7ntd9"><span class="c16">Analysis Phase:</span></h3><ul class="c7 lst-kix_g8upl37f117k-0 start"><li class="c13 li-bullet-0"><span class="c1">Correlation analysis and Linear regression:</span></li></ul><ul class="c7 lst-kix_g8upl37f117k-1 start"><li class="c3 li-bullet-0"><span>Run </span><span class="c2">correlationLm.R</span><span>, make sure to load </span><span class="c2">nvda_stock_data_sentimentVpercChange.xlsx</span><span>&nbsp;and </span><span class="c2">lcid_stock_data_sentimentVpercChange.xlsx</span><span>&nbsp;in your R workspace</span></li></ul><p class="c0 c5"><span class="c1"></span></p><p class="c0 c5"><span class="c1"></span></p><p class="c0 c5"><span class="c1"></span></p><p class="c5 c19"><span class="c1"></span></p></body></html>
