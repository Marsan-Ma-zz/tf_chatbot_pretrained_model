# Tensorflow chatbot pretrained model

This repository collect some pretrained model for the implementation [tf_chatbot_seq2seq_antilm](https://github.com/Marsan-Ma/tf_chatbot_seq2seq_antilm)


## Files

1. **example_model.tar.gz**

   A pre-trained model using twitter_en corpus from [this repository](https://github.com/Marsan-Ma/chat_corpus)
   params: size = 128, vocab_size = 50000, num_layers = 4

2. **twitter_en_big_model.tar.gz**

   A big-ass version of example_model.tar.gz, using twitter_en_big.txt.gz from [this repository](https://github.com/Marsan-Ma/chat_corpus)
   file is splitted, you could combine them into original file by:  
    `cat twitter_en_big.txt.gz* > twitter_en_big.txt.gz`  
   params: size = 256, vocab_size = 100000, num_layers = 4  
   

