![presidents_banner](https://github.com/thclough/inaugural_address_analysis/blob/main/presidents_banner.jpeg)
# War Presidents Inaugural Addresses: NLP Analysis

*By: Tighe Clough*

Inaugural addresses shape the expectation of the US populace. Such a speech "addresses" the entire nation regardless of difference in opinion. The impact of its messaging has extended to the rest of the world in relation to America's developing importance in global affairs. This messaging goes so far as to shape reality. People often judge a president from their persona and public relation skill rather than scrutinize the fine details of their actions and executed policy. 

During war, a president's words are particularly important because they serve to glue the country together to preserve American ideals or even the country itself. Therefore, it is of interest to compare how presidents purpose the inaugural address during war, or during the immediate lead-up to its formal declaration. I have chosen six addresses from such times: Lincoln's in 1861 (lead-up to Civil War), Wilson's in 1917 (WWI), Roosevelt's in 1941 (lead-up to WWII), Eisenhower's in 1953 (Korean War), Nixon's in 1969 (Vietnam War), and W Bush's in 2005 (War on Terror). This analysis leads to a deeper understanding of the general purpose of the inaugural address and the historical context of the selected addresses.

## Word Clouds

To start off, I created a word cloud for each speech to identify important words and themes:

![word_clouds](https://github.com/thclough/inaugural_address_analysis/blob/main/output/word_clouds.png)

These word clouds hint that presidents turn to the bedrock of America in troubling times. Words like "liberty", "freedom", "nation", and "Constitution" are all prevalent among the addresses. Safeguarding American values like freedom is often a rationalization for the US to initiate and escalate war.

## Sentiment Analysis

The polarity and subjectivity of a president's sentences determine the framing of each situation. Red dots represent a Republican president while blue dots represent a Democratic president:

![sentiment_plots](https://github.com/thclough/inaugural_address_analysis/blob/main/output/sentiment_plots.png)

All of these speeches seem to trend towards more positive. It would be morale-boosting to spread a positive message during wartime. The three earliest speeches seem to have more negative sentences than the latest three speeches. 

Eisenhower's sentences seem to be particularly positive because he stressed the victory of light (American values) over dark in his speech, especially in the conclusion. Although Lincoln has many positive sentences, he also has some of the most negative ones. Lincoln uses many sentences to condemn Southern states for seceding from the Union.

In conclusion, all presidents are more positive when they are more subjective. Presidents want to convey a message of positivity, but they are also expected to address reality and any negative events it may contain. While balancing these requirements, they are strategically passionate when optimistic and tend to be more factual and direct when delivering bad news.

It is also important to factor in the sequentiality of such data and how the mood of the speech changes through its course. Blue lines represent Democrats and red lines represent Republicans.

![ma_pol](https://github.com/thclough/inaugural_address_analysis/blob/main/output/ma_pol.png)

![ma_sub](https://github.com/thclough/inaugural_address_analysis/blob/main/output/ma_subj.png)

These graphs show sentiment over the course of each speech measured by sentence moving average. One notable finding is Wilson's uphill sentiment throughout his inaugural address. He works his way from a polarity score of 0 to around .25 by the end of the speech. He starts out by describing war on America's horizon but transitions to how the country will overcome this challenge.

It seems that other presidents' speeches progress with waves of sentiment. Eisenhower's speech ends on a positive note. Both of the Democrats seem to start their speeches with a more negative tone than the Republicans. In terms of subjectivity, Lincoln and FDR's speeches have rapid declines in subjectivity towards their endings. Lincoln concludes with statements such as "You have no conflict without being yourselves the aggressors" and "We are not enemies, but Friends." FDR concludes with a short factual story about George Washington and statements about the spirit of America.

## Vocab Similarity

Word choice provides a different avenue to compare the addresses. Word choice affects the connotation of a message and reflects the unique style of each president.
<p align="center">
<img src="https://github.com/thclough/inaugural_address_analysis/blob/main/output/vocab_heatmap.png"></img>
</p>

Surprisingly, FDR, George W. Bush, and Nixon constructed their addresses with similar vocabulary. Lincoln and Bush seem to have different speeches in terms of vocabulary. Lincoln used more complex vocabulary, while Bush opted for plainer speech.

A Sankey diagram is particularly useful in detailing the similarities and the degree of these similarities:

<p align="center">
<img src="https://github.com/thclough/inaugural_address_analysis/blob/main/output/vocab_sankey.png"></img>
</p>

As in the word clouds, this Sankey diagram shows common words associated with American values. These presidents commonly use the words "people", "freedom", and "constitution". Freedom is not only used to apply to the freedom of American people but the freedom of those affected by foreign wars. The use of "democracy" is mostly limited to FDR's address while the word "voices" is more unique to Nixon's. These isolated words hint at the themes of each address. For example, Nixon uses the word "voices" to talk about the different viewpoints on the Vietnam war.

## Structure

Sentence length and punctuation affect the cadence of each speech.


<p align="center">
<img src="https://github.com/thclough/inaugural_address_analysis/blob/main/output/sentence_boxplot.png"></img>
</p>


Lincoln has particularly long sentences with a median sentence length of around 20 words. Sometimes he delivers long flowery sentences to illustrate his points. FDR has the shortest sentences. FDR's paralytic illness (assumed to be polio) may have affected his breathing and physically limited the amount of words he could fit in a sentence.

Punctuation provides further data on speech structure:

<p align="center">
<img src="https://github.com/thclough/inaugural_address_analysis/blob/main/output/punctuation_barchart.png"></img>
</p>

Lincoln is asking many questions. Reading over his address, they seem to be mostly rhetorical questions arguing against secession from the Union. This graph also points to Lincoln having longer sentences with much fewer periods per 100 words than the other wartime presidents. FDR has many more periods and commas, implying more breaks in his speech. Nixon seems to draw from many different sources in his address with many direct quotes.

## Conclusion

Presidents do not follow a recipe when constructing their speeches; they each have their own unique style of deliverance. The style of each speech cannot be compared in complete isolation. The characteristics of each conflict affect structure and style. However, it can be said that each president stays true to the core theme of unity to strengthen support for American values. In current times of division, it is reassuring to know that in even the most severe episodes of history when American unity has shattered, it has always restabilized and persisted. 
