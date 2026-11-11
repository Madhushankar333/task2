sentiment analysis prompt
Multilingual Customer Review Sentiment Classification
Project Overview

This project classifies customer reviews into three sentiment categories: Positive, Negative, and Neutral.

The model analyzes the overall meaning and emotional tone of customer reviews rather than relying only on individual words. It supports multiple languages, including English, Hindi, Hinglish, and mixed-language reviews.

Sentiment Categories
Positive: Reviews expressing satisfaction, happiness, appreciation, or praise.
Negative: Reviews expressing dissatisfaction, disappointment, complaints, or criticism.
Neutral: Reviews containing factual information, descriptions, or no identifiable sentiment.
Key Features
Supports multilingual customer reviews.
Understands English, Hindi, Hinglish, and mixed-language text.
Handles spelling mistakes and grammatical errors.
Understands slang, abbreviations, and informal expressions.
Identifies dominant sentiment in mixed-opinion reviews.
Handles meaningless text and random characters.
Produces exactly one sentiment label.
Input Format

The system accepts customer reviews as plain text.

Example:

text
The product is excellent, and I love its quality.

Output Format

The system returns exactly one lowercase word:

text
positive


Possible outputs:

positive
negative
neutral
Sample Test Cases
Customer Review	Expected Output
Amazing product and fast delivery!	positive
bahut achha hai	positive
Very poor quality.	negative
Paisa barbaad ho gaya.	negative
The product arrived yesterday.	neutral
Abhi tak use nahi kiya hai.	neutral
Not bad, actually quite good.	positive
Good product, but delivery was very late.	negative
kSJDFGV LIUghfwueohf	neutral
Classification Guidelines
Understand the complete meaning of the review.
Identify the overall emotional tone.
Consider both positive and negative opinions.
Determine the dominant sentiment.
Classify meaningless or unclear reviews as neutral.
Return only one sentiment category.
Output Rules
Always use lowercase.
Return exactly one word.
Do not provide explanations.
Do not translate or summarize the review.
Do not include punctuation or additional text.
Applications
E-commerce customer feedback analysis.
Product review monitoring.
Customer satisfaction analysis.
Online shopping experience evaluation.
Automated feedback classification.
Conclusion

This project provides a simple multilingual sentiment classification system designed to identify customer opinions accurately and consistently across different languages and informal writing styles.
