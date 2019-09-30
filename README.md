# Social Opinion Gold Standard for the Malta Budget
A gold standard of annotated social opinion for the Malta Government Budget 2018. It consists of over 500 online posts in English and/or the Maltese less-resourced language, gathered from social networking services and newswires, which have been annotated with information about opinions expressed by the general public and other entities, in terms of sentiment polarity, emotion, sarcasm/irony, and negation.

## Annotations
Each online post contains the following metadata and annotation types:
	1. **Online Post Identifier**: unique numerical identifier for the online post;
	2. **Related Online Post Identifier**: numerical identifier for the parent online post (if any);
	3. **Source Identifier**: numerical identifier referring to the actual data source (e.g., website) of the online post; 
  4. **Source Name**: origin of the online post (e.g., Twitter, MaltaToday); 
	5. **Online Post**: textual string of the online post;
	6. **Sentiment Polarity**: a categorical value (3-levels) for the sentiment polarity of the online post (negative, neutral, positive);
	7. **Sentiment Polarity Intensity**: a categorical value (5-levels) for the sentiment polarity intensity of the online post (very negative, negative, neutral, positive, very positive);
	8. **Emotion (6-levels)**: a categorical value for emotion of the online post based on Ekman's six basic emotions (anger, disgust, fear, happiness, sadness, surprise); 
	9. **Emotion (8-levels)**: a categorical value for emotion of the online post based on Plutchik's eight primary emotions (joy, sadness, fear, anger, anticipation, surprise, disgust, trust); 
	10. **Sarcasm/Irony**: binary value, with 1 referring to sarcasm and irony in online posts;
	11. **Negation**: binary value, with 1 referring to negated online posts; 
  12. **Off-topic**: binary value, with 1 referring to off-topic online posts that are political but not related to the budget;
	13. **Maltese**: binary value, with 1 referring to online posts (full text or majority of text) in Maltese, and 0 referring to posts in English.

## Licenses
The dataset is licensed under the [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)] (https://creativecommons.org/licenses/by-nc-sa/4.0/) license.

Please cite [Cortis et al. 2019] (http://noisy-text.github.io/2019/accepted/74.html) in all publications using this dataset (see References below).

## References
@inproceedings{Cortis2019,
  title={A Social Opinion Gold Standard for the Malta Government Budget 2018},
  author={Cortis, Keith and Davis, Brian},
  booktitle={Proceedings of the 5th Workshop on Noisy User-generated Text (W-NUT)},
  pages={abc--def},
  year={2019}
}


