
# Opinion Mining

->Polarity (+,-)

Aspects - Explict - Explicit Aspect : Exterior
		    Explicit Aspect : Sound Quality
	  Implicit- Implicit Aspect : Weight Implied By Heavy Loads
		    Implicit Aspect : Price Implied bY cheap world

Comment 1 - Although this mobile phone is too heavy, it has nice exterior and is little cheap.
Comment 2 - The sound quality of this phone is very good.

1 = Sentiment classififcation at Document Level
2 = S.C. at Sentence Level
3 = S.C. at Word Level
4 = S.C. at Comparitive sentence analysis 

@ Sentiment Analysis - 1. Rule Based System 2. Automatic Method 

1. They perform on the basis of manually crafted rules.((estimate)Subjectivity + polarity)
   by utilizing a lexicon.
   Lexicon is a dictionary - of positive and negative opinions words and expression.
   There are several out there that are available to use.
   Eg sentiment_lexicon -- contain 155k words with subjectivity and polarity(associated)
      vader_lexicon
   So forms 2 list -- good and bad, then based on the words in teh text, a scores are generated
   If both are equal- return neutral, is good is high - positive and vice versa.
   Pros - No training Required , Easier to debug
   Cons - Not as accurate


2. Automatic method - This doesnot rely on rule but instaed of Machine learning. 
   Where some M.L ALgorithm is feed text and gives a corresponding polarity. 
   During the process the algo learns to give particular input witha particular output using 
   a optimization strategy. 
  Pros -  Scalable, More accurate 
  Cons -  Requires Training Data 


# We are going to analyse Twitter tweets, to access we need Twitter API, create a twitter Application account.

