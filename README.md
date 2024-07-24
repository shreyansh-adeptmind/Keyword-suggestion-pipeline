# Suggestion-Pipeline
-- The pipeline takes list of keywords as input and give **n**(default set to 20) similar keyword suggestions as output.

-- We are using Google Ads to genrate the corpus. Then we use cosine similarity to find similarity and suggest the words with scores that lie between given threshold values. The threshold values are obtained by the analysis done in optimalThreshold.ipynb
