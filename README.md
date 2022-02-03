# EmpatheticConversations-EC
This repository presents a database based on Empathetic Dialogues (ED), a databse created by Rashkin et al. with the purpose of cataloging empathetic conversation. The database presented (EC) contains a representative sample of ED, which has been evaluated by a series of experts and added a metric of the level of empathy present in each conversation . This evaluation is based on the Empathy Quotient (EQ) developed by Simon Baron-Cohen and Sally Wheelwright. 

EmpatheticConversations contains the following features: 
 
* Conv_id: An unique identifier for the conversation in the database. This also corresponds to the identifier in EmpatheticDialogues (ED). 
* Utterance_idx: The turn corresponding to the utterance in the conversation. 
* Context: A description of an emotional label given to the conversation. 
* Talker: A descriptor whether the utterance is done by the “Talker" or “Listener" role in the database.  
* Utterance: The text exchange of a person involved in the conversation. 
* Prompt: The description of the emotional situation the defines the conversation. 
* Ut_len: The length of the utterance measured by the characters present. 
* Sentiment: String that describes the probabilities of whether the utterance is positive, neutral, or negative. 
* Emotion: String that lists the probabilities that the utterance presents one of six emotions.
* Taxonomy: String that presents the three most likely taxonomy labels, along with its confidence score. The taxonomy labels are according to the IAB (Interactive Advertising Bureau) Tech Lab Content Taxonomy
* Intent: String that describes the probability that the utterance corresponds to one of 8 distinct intent labels. 
* Empathy: The empathy score of the conversation. It describes the amount of empathy according to 5 levels. It reflects the judgment of highly empathetic people. 

Additionally, a EmpatheticConversations_Plutchik contains another version of the database that codifies the emotional context into features based on Plutchik's emotion model. These features present 8 binary categories that represent the 8 basic emotions found by Plutchik, as well as an integer value that describes the intensity of the emotions present. The features are as follows: 

* PL_joy: Binary category referring to the presence of the emotion “Joy"
* PL_trust: Binary category referring to the presence of the emotion “Trust"	
* PL_fear:	Binary category referring to the presence of the emotion “Fear"
* PL_surprise:	Binary category referring to the presence of the emotion “Surprise"
* PL_sadness:Binary category referring to the presence of the emotion “Sadness"
* PL_disgust:Binary category referring to the presence of the emotion “Disgust"	
* PL_anger:	Binary category referring to the presence of the emotion “Anger"
* PL_anticipation:Binary category referring to the presence of the emotion “Anticipation"	
* PL_intensity: Integer category referring to the intensity of the emotion. The value “1" represent the highest intensity. Meanwhile, the value “3" represents the lowest intensity. 

The original database by Rashkin et al can be found in the following repository: 
https://github.com/facebookresearch/EmpatheticDialogues


# License

Please refer to the license file in the repository for information of the license.
