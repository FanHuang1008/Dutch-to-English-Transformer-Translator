# Dutch-to-English-Transformer-Translator
A transformer model that translates Dutch to English

The object of this project is to help me familiarize transformer model, which was introduced in a 2017 paper ["Attention Is All You Need"](https://arxiv.org/pdf/1706.03762.pdf).

[Hugging Face opus_books Dataset](https://arxiv.org/pdf/1706.03762.pdf) is used as the training and validation set. There are 16 languages available in it. Before training the model, make sure to change the source language and the target language in the configuration file ```config.py```. If pre-trained weights are available, put them in the ```./weights``` folder. Run the following code to train the model:

```
python3 train.py
```

After the model is trained, run the following code for the translation task. The program will ask you to enter the Dutch sentence that you want to translate:

```
python3 translate.py
```

References: \
https://www.youtube.com/watch?v=ISNdQcPhsts&ab_channel=UmarJamil \
https://www.youtube.com/watch?v=bCz4OMemCcA&ab_channel=UmarJamil
