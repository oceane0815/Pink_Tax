# Pink_Tax
[##Dropped## In "Google_trends_pink_tax_state_2014_to_2022.ipynb," the data is normalized by dividing the target state value by the average of baseline state value in each iteration. The baseline states include California, New York, Texas, and Illinois. [Choosing California, New York, Texas, and Illinois as baseline states is supported by their population size, economic and geographic diversity, and national influence. These factors ensure that they provide a stable, representative baseline for normalizing trends in data across the U.S.]]


There might be the dynamic issue with the baseline average from 2014-2022. To address that, I chose to use the highest value of California's Google Trends data as the base and modify the code as follows:


1) Instead of averaging the baseline states, I first extract the values for California. 2) I find the maximum value for California's Google Trends data and use that as the base value. 3) Each target state's value will be normalized against this base value.
