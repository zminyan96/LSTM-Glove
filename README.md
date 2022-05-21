# LSTM-Glove

In Glove+LSTM.ipynb, please omit the test part (Jump from "Create DataLoader" to "LSTM".

In Glove+LSTM_no padding.ipynb, please omit the test part as well (Jump from "DataLoader" to "Model" in "BiLSTM").

The differences between these two methods are: 1. In Glove+LSTM, I padded or truncated all sentences to 50 words.
2. In Glove+LSTM_no padding, the lstm is bidirectional.

I followed the paper arXiv:1702.03814v3 [cs.AI] 14 Jul 2017 to build the model. The thing that I didn't understand is the meaning of character-composed embedding in the first word representation layer.
