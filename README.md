#### Relative Switching Point based Dynamic Positional Representation for Code-Mixed Sentiment Analysis

## Abstract 
  <p> NLP applications for code-mixed (CM) or mix-lingual cases
have gained a significant momentum recently, the main reason being the prevalence of language mixing in social media
communications in multi-lingual societies like India, Mexico, parts of USA etc. Word embeddings are basic building blocks of any NLP system today, yet, word embedding
for CM languages is an unexplored territory. On the other
hand, it is known that positional info and/or sequence order
is an important aspect in NLP. Positional aspects are again in
discussion as people started realising that transformer based
models over-simplified positional info using sin/cos functions. There are several challenges for CM word embedding - spelling variations, word play, different languages etc. The major bottleneck is switching points, where the language
switches. These locations lack in contextually and statistical
systems fail to model this phenomena due to high variance in
the seen examples. In this paper we present our initial observations on applying positional encoding techniques for CM
language, specifically Hinglish (Hindi - English). Results are
only marginally better than SOTA, but it is evident that positional encoding could be an effective way to train position
sensitive language models for CM text.</p>


# PESTO Architecture
 ![alt text](https://github.com/mohammedmohsinali/PESTO/blob/main/PESTO_Architecture.png)

# Switch Point Attention
 ![alt text](https://github.com/mohammedmohsinali/PESTO/blob/main/Switch_Points_HeatMap.png)
  
# Authors
  * Mohsin Ali Mohammed(IIIT, Sricity)
  * Kandukuri Sai Teja(IIIT, Sricity)
  * Sumanth Manduru(IIIT, Sricity)
  * Parth Patwa(UCLA, USA)
  * Amitava Das(Wipro AI Labs)
