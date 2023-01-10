# War Presidents Inaugural Addresses: NLP Analysis

*By: Tighe Clough*

Inaugural addresses shape the expectation of the US populace. Such a speech "addresses" the entire nation regardless of difference in opinion. The weight of its messaging has expanded to the rest of the world in relation to America's developing importance in world affairs. This messaging goes so far as to shape reality. People oftentime judge a president from their persona and public relation skill rather than scrutinize the fine details of their action and executed policy. 

During war, a president's words are particularly important because they serve to glue the country together to preserve American ideals or even the country itself. Therefore, it is of interest to compare how presidents purpose the inaugural address during war, or during the immediate lead up to its formal declaration. I have chosen six addresses from such times: Lincoln's in 1861 (lead up to Civil War), Wilson's in 1917 (WWI), Roosevelt's in 1941 (lead up to WWII), 'Eisenhower's in 1953 (Korean War)', Nixon's in 1969 (Vietnam War)', and W Bush's in 2005 (War on Terror). This analysis leads to a deeper understanding of the general purpose of the inaugural address and the historical context of the selected addresses.

## Word Clouds

To start off, I created a word cloud for each speech to identify important words and themes:

![word_clouds](https://github.com/thclough/inaugural_address_analysis/blob/main/output/word_clouds.png)

These word clouds hint that presidents turn to the bedrock of America in troubling times. Words like "liberty", "freedom", "nation", and "Constitution" are all prevalent among the addresses. Safeguarding American values like freedom is often a rationalization for the US to initiate and escalate war.

## Sentiment Analysis

The polarity and subjectivity of a president's sentences decide the framing of each situation.

![sentiment_plots](https://github.com/thclough/inaugural_address_analysis/blob/main/output/sentiment_plots.png)

All of these speeches seem to trend towards more positive. It would be morale boosting to spread a positive message during war time. The three earliest speeches seem to have more negative sentences than the latest three speeches. 

Eisenhower's sentences seem to be particularly positive because he stressed the victory of light (American values) over dark in his speech, especially in the conclusion. Although Lincoln has many positive sentences, he also has some of the most negative ones. Lincoln use many sentences to condemn Southern states for seceding from the Union.

In conclusion, all president's are more positive when they are more subjective. Presiden's want to convey a message of positivity, but they are also expected to address reality and any negative events it may contain. While balancing these requirements, they are strategically passionate when optimistic and tend to be more factual and direct when delivering bad news.

It is also important to factor in the sequentiality of such data and how the mood of the speech changes through its course:

![ma_pol](https://github.com/thclough/inaugural_address_analysis/blob/main/output/ma_pol.png)

![ma_sub](https://github.com/thclough/inaugural_address_analysis/blob/main/output/ma_subj.png)

These graphs show sentiment over the course of each speech measured by sentence moving average. One notable finding is Wilson's uphill sentiment throughout his inaugural address. He works his way from a polarity score of 0 to around .25 by the end of the speech. He starts out by describing war on America's horizon but transitions to how the country will overcome this challenge.

It seems that other presidents' speeches progress with waves of sentiment. Eisenhower's ends on a positive note. Both of the Democrats seem to start their speeches with a more negative tone than the Republicans. In terms of subjectivity, Lincoln and FDR's speeches have rapid declines in subjectivity towards their endings. Lincoln concludes with statements such as "You have no conflict without being yourselves the aggressors" and "We are not enemies, but Friends." FDR concludes with a short factual story about George Washington and statements about the spirit of America.
