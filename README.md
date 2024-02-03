# TEXT CONVERSATIONAL USING TOPSIS
# TOPSIS

![TOPSIS-method-algorithm](https://github.com/ashnaarora251/textconversational/assets/157981667/97852ead-1037-4a86-bfa5-b65ff6a1bb76)

TOPSIS (Technique for Order Preference by Similarity to Ideal Solution) is a decision-making method used in multi-criteria decision analysis. It aims to determine the best alternative from a set of options by considering both the similarity to the ideal solution and the dissimilarity to the negative-ideal solution. TOPSIS is particularly useful when evaluating alternatives based on multiple criteria.

**The key steps in TOPSIS are as follows:**

**Normalization of Decision Matrix:**
Normalize the decision matrix, which consists of the performance values for each alternative across different criteria. Normalization ensures that each criterion is on a comparable scale.

**Weighted Normalized Decision Matrix:**
Apply weights to the normalized decision matrix to reflect the relative importance of each criterion. This step allows decision-makers to express their preferences and priorities.

**Ideal and Negative-Ideal Solutions:**
Identify the ideal solution, where each criterion is maximized, and the negative-ideal solution, where each criterion is minimized. These solutions represent the best and worst possible outcomes, respectively.

**Distance Calculation:**
Calculate the Euclidean distances between each alternative and both the ideal and negative-ideal solutions. This step quantifies how close or far each alternative is from the best and worst scenarios.

**Relative Closeness:**
Determine the relative closeness of each alternative to the ideal solution by calculating the ratio of the distance to the negative-ideal solution over the sum of distances to both the ideal and negative-ideal solutions.

**Ranking:**
Rank the alternatives based on their relative closeness. The alternative with the highest relative closeness is considered the most preferred.

TOPSIS provides a systematic approach for decision-makers to evaluate and rank alternatives based on multiple criteria, taking into account both positive and negative aspects. It is widely used in fields such as operations research, management, and engineering for decision support in complex decision-making scenarios.

# TEXT CONVERSATIONAL

"Text conversational" refers to text data or language that resembles the style and structure of natural human conversations. NLP techniques and models are often designed to handle conversational text, and understanding its characteristics is crucial for tasks like chatbot development, sentiment analysis, dialogue systems, and more.

Here are some key aspects of text conversational in terms of NLP:

**Informality and Colloquial Language:**
Conversational text is typically more informal and may include colloquial expressions, slang, or everyday language used in spoken communication.

**Sentence Structure and Length:**
Conversational text may exhibit a more varied sentence structure compared to formal writing. It can include shorter sentences, sentence fragments, and a more dynamic use of punctuation.

**Context Awareness:**
Conversational models need to be context-aware. Understanding and referencing previous parts of the conversation is essential for generating relevant and coherent responses.

**Handling Ambiguity and Uncertainty:**
Conversational text often involves ambiguity, uncertainty, and implicit meanings. NLP models need to be able to handle these nuances to provide accurate interpretations.

**User Intent Recognition:**
In conversational NLP, recognizing the user's intent is crucial for generating appropriate responses. This involves understanding the purpose behind user queries or statements.

**Emotion and Sentiment:**
Conversational text may convey a range of emotions and sentiments. NLP models designed for sentiment analysis in conversations should be able to detect and understand these emotional nuances.

**Dynamic Interaction:**
Conversational systems often involve dynamic interactions with users. Models need to handle real-time updates, user prompts, and changing contexts within a conversation.

**Handling Multi-turn Dialogues:**
Conversational NLP deals with multi-turn dialogues where a sequence of user and system utterances form a meaningful conversation. Models must maintain context across these turns.

# TOPSIS FOR PRETRAINED MODELS
Applying topsis to find best Pre-trained Model for Text Conversational
## **1. Methodology**
1. Select 5 pretrained models.
2. Generate reponses to some prompts.
3. Evaluate models on the basis of parameters: BLEU, ROUGE, Reponse Length.
4. Compare the pretrained models by applying Topsis


## **2. Input / Output**
<p>Input</p>
<img src="https://github.com/ashnaarora251/textconversational/assets/157981667/1fe34f17-b737-4d0c-9e0f-99db3622d6b9">



<p>Output</p>
<img src="https://github.com/ashnaarora251/textconversational/assets/157981667/87c5341e-d1a8-4d7c-9272-bb8b6e21600e">




## **3. Evaluation Metrics**
1. BLEU
2. ROUGE Scores
3. Reponse Length


## **4. Models Used**
1. microsoft/DialoGPT-medium
2. Pi3141/DialoGPT-medium-elon-2
3. microsoft/DialoGPT-large
4. microsoft/DialoGPT-small
5. satvikag/chatbot


## **5. Result**
<img src="https://github.com/ashnaarora251/textconversational/assets/157981667/6cf78bbe-c2f3-47a8-92cf-eabd73ddcf8b">

