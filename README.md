# naive-bayes
Naive Bayes is a quick and dirty way to classify data but is simple to implement. This is a nice way to brute force a result by calculating simple statistics assuming the data is normally distrubuted and an assumption that there is independence in the data, which is almost never true in reality. 

## Spam vs Ham

I used a [dataset](https://archive.ics.uci.edu/ml/datasets/Spambase) from the UCI machine learning repository to perform a classic example of classifying email into spam vs ham which Naive Bayes can perform relatively well on.

## Notes

The implementation source code came from this [tutorial](https://machinelearningmastery.com/naive-bayes-classifier-scratch-python/) and credit goes to Dr. Jason Brownlee who wrote it. I adjusted the implementation to fit my needs for the dataset that I wished to clean and classify. The original use case was predicting diabetes. 
