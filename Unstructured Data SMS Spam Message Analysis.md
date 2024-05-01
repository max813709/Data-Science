# <strong> Unstructured DataModel SMS Spam message analysis using RapidMiner </strong> #

## <strong> Description </strong> ##

Manipulates the data, utilizes a decision tree and random forect to manipulate the data in a user friendly way.

## <strong> Technologies Used </strong> ##

[RapidMiner Studio V.10.3.1](https://www.uipath.com/product/studio): Development Environment.

[Microsoft Excel]: Used to store customer information.

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/ded8c956638f8d0e6783f7b8fe0321c4e7b56469/2024-03-30%2011.56.30.png">
![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/13fa5e69ce4f748ec9b835c252a9b0d8cb643406/2024-03-30%2011.57.53.png">
![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/b7268aad2530c825ba9f17d706c5ed2205a8c595/2024-03-30%2011.59.04.png">


## <strong> Features </strong> ##
• Utilizes a Data Dictionary
•	There is about a 10% rate of spam messages compared to the approximately 90% messages that are not spam. We handle this imbalance by acknowledging that most spam messages are not marketed after text people and that spam messages use other ways to interact with consumers.
•	Utilizes a wordcloud, which helps visualize the commonly used phrases and words in the SMS messages looked at for this study. They are altered based on frequency and visualized as more distinct based on this. It helps us visualize distinctly the words sent via SMS.
•	We can also see the words which contributed the most to the classifying the review as positive or  negative.  For  example,  we  can  observe  words  like high,  unusual,  outrageously, etc. contributed to the sentiments being negative (score is less than 0).
•	Our computed sentiment scores also show a correlation with the original product ratings the reviewers gave between 1 and 5. The higher the rating, the higher the average sentiment of the reviews in that rating.
This gives us confidence that the reviews are represented somewhat well by the ratings, and that the SentiWordNet sentiment analysis algorithm has worked well.
•	The model performs very well on the training and testing data, in terms of both the Precision and the Recall.
• The random forest model compared to the pruned random forest model in terms of accuracy, recall, and precision for SMS spam detection is more accurate overall.
• We found very few SMS spam messages received compared to not spam, and most of the messages sent were grammatically incorrect or acronyms. 
• The company should establish more channels for receiving feedback from the younger age group in order to better understand their needs and tailor products accordingly.
• SMS messages targeted to resemble not spam messages should be targettted and personalized informally to maximize this need to market using spam sms messages.
• Through spam SMS messages the company can target people of different age groups by tailoring their messages to the way a user writes and offer special promotions to attract consumers.

![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/c0661a62b8c8eb702f588738a4d3ceaf360e8696/2024-03-30%2012.00.21.png">
![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/32f6549fa04acf97e65a5b4c6f460c73d525962d/2024-03-30%2012.02.17.png">
![]()<img width="723" alt="image" src="https://github.com/matthew813709/Gitimages/blob/e5b3ea712c8fd5f1463705f9e1a541da516d3ad4/2024-03-30%2012.03.59.png">


## <strong> Contributors </strong> ##
Matthew Emsak

## <strong> License </strong> ##
This project uses the following license: MiT.
