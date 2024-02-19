# NLP Generative AI: Family Group chat
Family group chat Natural Language Processing. Exploratory Analysis, Sentiment Analysis, LDA topic modeling, and text generation
Please click 'Open in Colab' to view the Plotly interactive visualizations.

<img width="1356" alt="Screen Shot 2024-02-14 at 5 04 00 PM" src="https://github.com/michaeltiede/family_group_chat/assets/63974875/2a87fd45-ffad-46dd-a811-cacda2b710f2">

My family since 2016 has had a GroupMe group chat, consisting of my cousins, aunts, uncles, and grandparents (25 people in total). I decided to take these messages and explore the data! I was able to analyze and answer questions such as "Who sends the most messages?" "When are the most messages sent by date?" "Are there trends throughout the year?". I also analyzed the sentiment of the messages by each individual, and scored based on positive or negative sentiment. I looked for common words and phrases by using tokenization, stemming, and lemmatization. Bi-grams and tri-grams also were used for 2 and 3 letter phrases. 

More advanced Natural Language Processing techniques were Latent Direllect Allocation Topic Modeling to identify common topics that the unsupervised model could identify. Some topics identified where phrases such as "happy birthday" and sibling relationships (Myself, Michael, and my sister Rachel were a topic) and my cousins (Lucas and Linnea) were put into a topic, along with the words "Pretty Amazing":) . I have the best cousins!

Lastly, I generated phrases and paragraphs from the text data. I used bi-grams and tri-grams to generate the paragraphs. I started with tri-grams and then generated the most probable word to come next. Once there was no tri-gram avaiable, it went to bi-grams to continue the paragraph. I was able to create interesting paragraphs with decent coherence and understanding! Example: "Play gophers championship hope get final game career oh many mixed emotions win situation" & "Profile pics fun scroll see transformation"

Overall, In this project I wanted to improve my skills in Natural Language Processing, ML model building, and AI tools. I plan to continue to improve the model pipeline and training to create morea insightful conclusions.

Word Cloud of most common words in the chat:

![image](https://github.com/michaeltiede/family_group_chat/assets/63974875/33852153-1b62-4034-b132-df4b909ab0f5)

Most Messages by person:

<img width="1284" alt="Screen Shot 2024-02-14 at 5 05 42 PM" src="https://github.com/michaeltiede/family_group_chat/assets/63974875/c526db06-57be-4abe-9a32-e6105c529bcc">



