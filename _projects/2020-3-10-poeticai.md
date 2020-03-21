---
title: 'Poetic AI'
subtitle: 'Generating Poetry through Fine-Tuning on GPT-2'
date: 2020-01-01 00:00:00
description: Fine tuning GPT-2 to generate poetry.
featured_image: '/images/poetic/unsplash_poetry.jpg'
---

![](/images/poetic/art-lasovsky-unsplash_narrow.jpeg)

# Poetic AI
Poetic AI is a short project I did with Dawit Gebregziabher[^1] as part of Comp 119 (Big Data) during my Masters program at Tufts. The project is a natural language model that can write poetry given a short prompt.

[^1]: link to Dawit's github or linkedin

The model was created by fine tuning the GPT-2[^2] small and medium models on the Gutenberg Poetry Corpus[^3]. It required a lot of parameter tuning and failed poems to get results that look reasonable (see below).

[^2]: <a href="https://openai.com/blog/better-language-models/">https://openai.com/blog/better-language-models/</a>

[^3]: <a href="https://github.com/aparrish/gutenberg-poetry-corpus">https://github.com/aparrish/gutenberg-poetry-corpus</a>

Check out the colab notebook we ran our code in <a href="https://colab.research.google.com/drive/1KyOQga7G-NivE7QUPRnzGnBjsaLXy6LG">here</a>. Scroll down to check out some of the poetry we generated.

---
## Poetry samples
### Given the seed word 'Love'
```html
Love
Is the first thing in the world,
We all know.
But I’ll tell you all, love,
Love gives us more
Than all words ever told;
When it has taken hold of us,
I will tell you all,
Love is the first thing.
We all know.
```

### Given the seed phrase 'Beautiful Sunsets'
```html
Beautiful Sunsets in a far away place
As for you from afar, the day is gone when the suns begin
To glow, and your eyes of peace will not be sad or sad,
You have never been alone to this fair and pleasant town,
But I have known you at the close and long ago,
And I know you remember well your fair and lovely face,
And the way in which the morning starlight blanches the sun.
I remember all of you, happy lovers dear,
And the great things that were told to you before your death,
And the things that you spoke of in your heart so true.
Of all the people in that town, none are in all the world,
The richest are all, and the least are poor, and many a great
The most humble are the poor, and these are the best."
```

### A failed poem
The parameter tuning wasn't set quite right here (or maybe it was depending on how much you like this poem).
```html
Love
I fear, and fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
And fear grow,
```

## Acknowledgements
Cover image by <a href="https://unsplash.com/@alvaroserrano?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Álvaro Serrano</a> on Unsplash

Featured image by <a href="https://unsplash.com/@artlasovsky?utm_source=unsplash&utm_medium=referral&utm_content=creditCopyText">Art Lasovsky</a> on Unsplash