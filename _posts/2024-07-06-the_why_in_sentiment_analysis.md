---
layout: post
title: "Chasing the WHY in sentiment analysis"
tags:
- Churn
- Interactive
- Product Analytics
thumbnail_path: blog/placeholder_number_one/ask-customer-feedback.png
external_url: "https://deepnote.com/app/jeanie-oh/Interviews-8df4f567-748f-4a9f-b18c-3f9fea813441"
---

Sentiment analysis is a fantastic tool for summarising customer feedback. But wouldn't it be great to know more detail as to WHY they are delighted or dissatisfied? By leveraging the NLTK library and Naive Bayes algorithm, we isolate key words that give us a clue into WHY customers are satisfied or deeply disatisfied with a particular product. The idea is that these words will provide us actionable insights to augment what is working to optimise profit or address the most pressing sources of frustration to prevent churn.

I will walk us through the whole process from data loading, data cleansing, tokenizing to ultimately drawing up the final visualisations and insights for a hypthetical context so that you can apply these techniques in your own data.

First of all, the data is taken from a music website where users write extensive reviews on what they love and hate about each album/song. Below is a sample of one row:

{% include figure.html path="blog/placeholder_number_one/sampleData.png"}

{% include figure.html path="blog/placeholder_number_one/sentiment_chart.png" alt="Analysis Results" url=page.external_url %}

You can view the details on my [Deepnote Project]({{ page.external_url }}):

<iframe height="400" src="https://deepnote.com/app/jeanie-oh/Interviews-8df4f567-748f-4a9f-b18c-3f9fea813441?__embedded=true" title="Interviews" width="800" allowfullscreen></iframe>






