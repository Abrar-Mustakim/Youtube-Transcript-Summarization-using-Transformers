# Youtube-Transcript-Summarization-using-Transformers

The Project was done in Google Colab. After uploading the colab file in github, some of the outputs line got interupted. Sorry for the inconvenience<br>

I have used 2 different models which was pre-trained for text summarization. For YouTube Transcription, I have used a library. One of the two models are <b>Transformers</b> and other one is <b>BART</b>. I have presented them sequentially. 

The reason behind choosing this was I was previously introduced with Higginface models like Transformers, Stable Diffusion AI. This is the reason I knew some of the works like sentiment analysis, summarization and text to image generation. This is the reason I have choosen this problem interest.

Along with Transformers, I have also applied these algorithms: <br>

<p><b>LexRank Summarizer:</b> This is an unsupervised approach inspired by Google’s PageRank algorithm. It finds the relative importance of all words in a document and selects the sentences which contain most of those high-scoring words. The scoring of sentences is determined by using the graph matrix. This connectivity matrix is based on intra-sentence cosine similarity. The sentences are ranked according to their similarities. To implement the LexRank technique, python contains a library LexRank. After importing STOPWORDS and LexRank sub-libraries, we can generate a summary by using the latter one as a function and the former one as an input parameter.</p></br>

<p><b>TextRank Summarizer:</b> This algorithm also gets inspiration from the page rank concept. It is more simplistic than LexRank. This platform removes sentences with highly duplicitous by using the post-preprocessing step. </p></br>

<p><b>Luhn Summarizer:</b> It was published in 1958 by IBM researcher, Peter Luhn. It looks at the window-size of non-important words between words of high importance. Also, the sentences occurring near the beginning of a document gets higher weight. First, this algorithm determines which words are more significant towards the meaning of the document. Finding the most common words in the document and taking a subset of those that are not common words but still important are the next steps. To implement this technique, we can use the Sumy library in python.</p></br>
  
  
  
<p><b>LSA(Latent Semantic Analysis) Summarizer:</b> This brand-new algorithm combines term frequency with singular value decomposition. In python, this algorithm works as follows: — Convert a document into a vectorized bag of words using CountVectorizer library — Encode the original data into topic encoded data — Fit and transform single value decomposition on the bag of words using TruncatedSVD library — Determine the strength of each part of the sentence effectively — Extract out the final sentences from topics</p></br>


Thank You
