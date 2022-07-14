# SarcOji
Labeled Sarcasm Dataset with Emojis compiled from 5 Publicly Available Sarcasm Datasets viz

a) Sarcasm Dataset harvested from Twitter by Aniruddha Ghosh and Tony Veale. 2016. Fracking sarcasm using neural network. In Proceedings of the 7th workshop on computational approaches to subjectivity, sentiment and social media analysis, pages 161–169.

b) Jayashree Subramanian, Varun Sridharan, Kai Shu, and Huan Liu. 2019. Exploiting emojis for sarcasm detection. In International Conference on Social Computing, Behavioral-Cultural Modeling and Prediction and Behavior Representation in Modeling and Simulation, pages 70–80. Springer.

c) Silviu Oprea and Walid Magdy. 2019. isarcasm: A dataset of intended sarcasm. arXiv preprint arXiv:1911.03123.

d) Debanjan Ghosh, Avijit Vajpayee, and Smaranda Muresan. 2020. A report on the 2020 sarcasm detection shared task. arXiv preprint arXiv:2005.05814.

e) SemEval'22 Intended Sarcasm SubTask A for Identifying Sarcasm on English dataset: https://sites.google.com/view/semeval2022-isarcasmeval

SarcOji has a total of 29377 text records with emojis

There are 11448 Sarcastic Texts and 17929 are Non-Sarcastic

This dataset has following attributes

i) Text : Text with emojis

ii) Sarcastic: 0 or 1 to indicate non-sarcastic or sarcastic text respectively.

iii) Emojis: List of emojis in the text

iv) MaxEmoji: Most frequent emoji in the text

v) MaxEmojiNumOccurence: Frequency of MaxEmoji in the text

vi) MaxEmojiPos: Position of MaxEmoji at Left, Middle, Right (0,1, or 2 respectively) from the text

vii) TextSWN: Text sentiment score using SentiWordNet

viii) TextVader: Text sentiment score using VADER

ix) TextTextBlob: Text sentiment score using TextBlob

x) EmojiSWN: Combined sentiment score of all emojis using SentiWordNet

xi) EmojiVader: Combined sentiment score of all emojis using VADER

xii) EmojiTextBlob: Combined sentiment score of all emojis using TextBlob

xiii) MEmojiWN: Sentiment score of MaxEmoji using SentiWordNet

xiv) MEVader: Sentiment score of MaxEmoji using VADER

xv) METB: Sentiment score of MaxEmoji using TextBlob

xvi) ESR: Sentiment score of MaxEmoji using Emoji Sentiment Ranking



You can Cite Us with:
@inproceedings{grover-banati-2022-understanding,
    title = "Understanding the Sarcastic Nature of Emojis with {S}arc{O}ji",
    author = "Grover, Vandita  and
      Banati, Hema",
    booktitle = "Proceedings of the The Fifth International Workshop on Emoji Understanding and Applications in Social Media",
    month = jul,
    year = "2022",
    address = "Seattle, Washington, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2022.emoji-1.4",
    pages = "29--39",
  }
