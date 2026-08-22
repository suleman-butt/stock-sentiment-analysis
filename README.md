# Stock Price Movement and Social Media Sentiment Correlation
##### Comparative Analysis of Social Media Sentiment and Stock Price Correlation: NextEra (NEE), Palantir (PLTR), Procter and Gamble (PG), Nvidia (NVDA), and Tesla (TSLA)

#### This Project is available on 
GitHub: https://github.com/1010sb/StockSentimentAnalysis.git 
GitLab: https://gitlab.com/1010sb/StockSentimentAnalysis.git

here is new changes

An in-depth exploration of the intricate relationship between social media sentiment and stock price movements.

This study investigates the intricate relationship between social media sentiment, specifically on the StockTwits platform, and the fluctuations in stock prices for five prominent companies: Procter & Gamble (PG), NextEra (NEE), Nvidia Corporation (NVDA), Palantir (PLTR), and Tesla Inc (TSLA). Using statisti-cal tools like the Spearman Correlation Coefficient and P-Values, the analysis quantifies these connec-tions over a substantial period from June 1, 2020, to June 30, 2023, encompassing a dataset of 4,160,867 tweets pertaining to these corporations. The research unveils distinct correlation patterns among these entities, shedding light on their varying susceptibilities to social media sentiment fluctua-tions. Procter & Gamble and NextEra exhibit "Very Weak" correlations, suggesting minimal impact of social media sentiment on their stock prices. In contrast, Nvidia Corporation shows a "Weak" correlation, implying sentiment's role alongside other factors in shaping stock prices. Palantir demonstrates a "Mod-erate" correlation, indicating a noticeable influence of social media sentiment, while Tesla Inc stands out with a "Moderate to Strong" correlation, underscoring significant sentiment impact on its market perfor-mance. These findings provide valuable insights for investors and financial analysts, highlighting the importance of comprehending varying degrees of susceptibility among these companies to social media sentiment fluctuations. Companies with weaker correlations may continue relying on conventional mar-ket drivers, while those with stronger correlations, like Tesla Inc, emphasize the need for vigilant moni-toring of online discussions and public perception. In conclusion, this research underscores the multifac-eted relationship between social media sentiment and stock price movements among leading compa-nies, stressing the significance of considering sentiment in financial analysis alongside other critical market drivers, within the ever-evolving financial landscape.

## Methodology Flowchart
![Thesis_Methodology_1](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/0247ddaf-149e-4d03-9052-7c27b342561c)


 
The research process is visually represented in the above Figure through the Methodology Flowchart.
## Social Media Data – StockTwits

The following table demonstrates that the number of collected tweets varies for each company. In total I gathered 4,160,867 tweets. Notably data collection for Palantir began on October 1st, 2020, due to its IPO on September 30th (Levy, 2020). Among these selected companies is NextEra (NEE) with the tweet count of 13,585 tweets while Tesla (TSLA) leads with a count of discussion on the StockTwits platform, with a total of 2,911410 tweets.

![Tweet_count](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/67e667cc-8744-4557-8fc8-33f430d18bcb)

## NextEra (NEE)

To sum it up when looking at NextEra we can observe a very weak positive correlation, between daily sentiment scores and daily stock price changes. This means that as sentiment increases there is a mi-nor tendency for stock prices to show some positive movement. The presence of the associated regres-sion line, which has a slightly upward slope further supports the idea of a noticeable yet relatively weak positive connection, between daily sentiment scores and daily stock price changes.
![NEE_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/3ba5faff-a3c8-46e3-990c-dd3a3391b258)

## Palantir (PLTR)
To summarize based on a Spearman correlation coefficient of 0.4786 and a low p value of 0.000000 for Palantir (PLTR) we can conclude that there is a significant and moderate positive correlation, between daily sentiment scores and daily stock price changes. The data indicates that when there is a rise, in sentiment expressed in social media conversations it is likely that Palantir's stock prices will also show a trend. Additionally the presence of a regression line with a slope supports the idea that there is a moder-ate positive connection between daily sentiment scores and daily changes, in stock prices.
![PLTR_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/63d378d8-b43e-499e-994a-5db1841dea69)

## Procter and Gamble (PG)
To summarize the Spearman correlation coefficient of 0.1062, along with the p value of 0.003077 for Procter and Gamble (PG) indicates a significant but relatively weak positive correlation between daily sentiment scores and daily stock price changes. Moreover the presence of a regression line with an slope further supports the notion of this apparent yet somewhat modest positive association, between daily sentiment scores and daily stock price changes.
![PG_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/17c97188-9b20-4895-bba8-d71f6520c111)

## Tesla (TSLA)
To summarize the Spearman correlation coefficient of 0.4991 along with the p value of 0.00000 for Tesla Inc (TSLA) indicates a statistically significant and moderately strong positive correlation between daily sentiment scores and daily changes in stock prices. This correlation suggests that as sentiments in so-cial media discussions increase with positive sentiment there is a tendency for Tesla stock prices to move in a positive direction. Additionally the presence of a sloping regression line further supports this relationship shedding light on the significant impact of social media sentiment, on Tesla stock price dy-namics and market behavior.
![TSLA_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/39313288-567b-4aa7-a2a5-4ac24671f59d)

## Nvidia (NVDA)
To sum it up when we look at the Spearman correlation coefficient of 0.3018 and the p value of 0.00000, for NVIDIA Corporation (NVDA) it suggests that there is a statistically significant but somewhat weak positive relationship between daily sentiment scores and daily stock price changes. This means that as positive sentiment in social media discussions goes up we might see a slight inclination, for NVIDIAs stock prices to move in a direction although the connection is not particularly strong.
![NVDA_spearman_correlation_plot](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/5c4beb8b-5474-4426-942d-7e06aabc1ec0)

## Comparative Analysis of Correlation Patterns
When it comes to analysis understanding the connection, between social media sentiment and stock price movements is incredibly important. Table 2 offers an overview of this relationship for five known companies; Procter & Gamble (PG) NextEra (NEE) Nvidia Corporation (NVDA) Palantir (PLTR) and Tes-la Inc (TSLA). The Spearman Correlation Coefficient, along with its P Value helps determine the strength and significance of this correlation.

![comparison](https://github.com/1010sb/StockSentimentAnalysis/assets/96765388/7ca8a5a5-b98e-4e40-8c19-686983cdb7f7)

Starting with the group, Procter & Gamble and NextEra show " Very Weak" correlations. These compa-nies have correlation coefficients of 0.1062 and 0.1394 respectively accompanied by P Values. These statistics suggest that social media sentiment fluctuations have impact on their stock prices. It becomes clear that other factors exert an influence on how these companies perform in the market.
Moving on to the group Nvidia Corporation stands out with a "Weak" correlation. With a correlation coef-ficient of 0.3018 and a low P Value this company demonstrates that sentiment does play a role in influ-encing its stock price albeit, to an extent. This indicates that while social media sentiment affects Nvidia Corporations stock prices to some degree there are also contributing factors at play in their market dy-namics.

In the final group Palantir and Tesla Inc provide insights. Palantir demonstrates a correlation denoted as "Moderate " backed by a correlation coefficient of 0.4786 indicating that its stock prices are influenced by social media sentiment to some extent. On the hand Tesla Inc takes the lead, with a correlation classi-fied as "Moderate to Strong " boasting a correlation coefficient of 0.4991. This highlights the impact of social media sentiment on Teslas stock prices underscoring the role of public perception and online dis-cussions in shaping its market performance. These findings shed light on how these companies differ in their susceptibility to fluctuations in social media sentiment thereby revealing the complexity, in todays markets.

## Conclusion
This investigation focused on exploring how social media sentiment on StockTwits relates to the changes, in stock prices for five known companies; Procter & Gamble (PG) NextEra (NEE) Nvidia Corporation (NVDA) Palantir (PLTR) and Tesla Inc (TSLA). To understand this relationship we used the Spearman Correlation Coefficient and P Values. During the period of June 1 2020 to June 30 2023 a total of 4,160,867 tweets were collected for these companies.

The study revealed correlation patterns among these companies. Procter & Gamble and NextEra showed a "Very Weak" correlation indicating that their stock prices are not significantly influenced by so-cial media sentiment. On the hand Nvidia Corporation displayed a "Weak" correlation suggesting that sentiment does play a role but is not the dominant factor affecting its stock prices. Palantir demonstrated a "Moderate" correlation indicating that social media sentiment has an impact on its stock prices. Lastly Tesla Inc stood out with a "Moderate to Strong" correlation emphasizing that social media sentiment has an influence, on its market performance.

These findings provide valuable insights for investors and financial analysts, emphasizing the im-portance of comprehending the varying degrees of susceptibility among these companies to social me-dia sentiment fluctuations. Companies with weaker correlations, such as Procter & Gamble and Nex-tEra, may continue to rely primarily on traditional market drivers. Conversely, companies like Tesla Inc, with stronger correlations, are notably sensitive to public sentiment, emphasizing the need for vigilant monitoring of online discussions and public perception.
This study not only illuminates the complex interplay between social media mood and stock price changes but it also suggests various directions for further investigation. First and foremost it is important to make it clear that correlation does not indicate causation. This encourages deeper investigation of causal connections between social media opinion and stock price behavior. Examining the effects of outside variables, such as macroeconomic circumstances, business-specific news, and industry-specific events, can help to get a more complete knowledge of the elements that affect stock price. Further-more combining cutting edge sentiment analysis methods with machine learning models can improve the accuracy of next research projects.



