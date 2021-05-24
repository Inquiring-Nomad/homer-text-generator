**Using a pretrained transformer to generate Homer-like text**

https://github.com/huggingface/transformers

🤗 Transformers provides thousands of pretrained models to perform tasks on texts such as classification, information extraction, question answering, summarization, translation, text generation and more in over 100 languages. Its aim is to make cutting-edge NLP easier to use for everyone.


🤗 Transformers provides APIs to quickly download and use those pretrained models on a given text, fine-tune them on your own datasets and then share them with the community on our model hub. At the same time, each python module defining an architecture is fully standalone and can be modified to enable quick research experiments.


🤗 Transformers is backed by the three most popular deep learning libraries — Jax, PyTorch and TensorFlow — with a seamless integration between them. It's straightforward to train your models with one before loading them for inference with the other.



**Homer** 

https://en.wikipedia.org/wiki/Homer

Homer (/ˈhoʊmər/; Ancient Greek: Ὅμηρος [hómɛːros], Hómēros) was the presumed author of the Iliad and the Odyssey, two epic poems that are the foundational works of ancient Greek literature. 

**Model**

We are using https://huggingface.co/nikokons/gpt2-greek model and fine-tune it on Homer's translated Iliad and Odyssey