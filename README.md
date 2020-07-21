# English-Hindi-Translation-using-Transformer

Machine translation using Transformers

Dataset used  [The IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel) 

### Predicted translations(8 Epochs)

```
translate("Trade has stopped ")
Predicted translation: व्यापार का रोक दिया गया है । 
```

```
translate("This is the problem we have to solve .")
Predicted translation: इस समस्या के लिए एक साथ समस्या है जिससे हम किसी समस्या को हल करना चाहते हैं ।
```

```
translate("Very Less employment opportunities are produced")
Predicted translation: रोजगार की प्रतिभूति के लिए बहुत कम होती है ।
```

```
translate("Union is strength")
Predicted translation: संयुक्त संयोजन । 
```

```
translate("Union of india includes several states")
Predicted translation: भारत में संयुक्त राज्य सभा के विभिन्न राज्यों में से एक है ।  । 
```

## Transformer

![Transformer](./images/transformer.png)

### Attention

![Scaled dot product attention](./images/scaled_dot_product_attention.png)

![Multi head Attention](./images/multi_head_Attention.png)

## References

<https://www.tensorflow.org/tutorials/text/transformer>

 [Attention Is All You Need](https://arxiv.org/abs/1706.03762)

Anoop Kunchukuttan, Pratik Mehta, Pushpak Bhattacharyya. [The IIT Bombay English-Hindi Parallel Corpus](http://www.cfilt.iitb.ac.in/iitb_parallel/lrec2018_iitbparallel.pdf
). Language Resources and Evaluation Conference. 2018.
