## Adverse Media Detection using Transfer Learning on BERT Pretrained Model

The notebook is used for detection of Adverse News or News which can put dealings with businesses on a risk. The BERT pre-trained model was used which was retrained on custom scraped data from Google News. 

Entity | Value
------------- | -------------
Challenges  | Noise, Relevance and Less Data.
Feature Engineering  | Tokenization, Padding.
Models Used | BERT - Cased.
Optimizer |Adam Optimization 

### Performance

Multi-class classification problem.

Markup : * 0 - Negative
	 * 1 - Neutral
	 * 2 - Positive

Entity | Value
------------- | -------------
Training Accuracy | 97.22% - 10 Epochs  
Validation Accuracy |  84.3%
Test Accuracy | 84.84%

Precision  |  Recall | F1-score |  Support
---------- | ------- | -------- | --------
0   |    0.90  |    0.90   |   0.90   |     10
1   |    0.82   |   0.88  |    0.85   |     16
2   |    0.83   |   0.71  |    0.77    |     7

I'm always open to dicussions and improvements so please feel free to reach out to me [here](https://www.linkedin.com/in/taritroghoshal/ "here").



