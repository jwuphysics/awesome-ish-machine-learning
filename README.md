# Awesome-ish Machine Learning Tools

A modestly curated list of deep learning tools, guides, and examples. Most of these are in Python (🐍) and use Pytorch (🔥). **Bolded** items indicate my personal favorites.

*🚧🚧 Under construction 🚧🚧* 

# General courses

[**Coursera - Machine Learning (Andrew Ng)**](https://www.coursera.org/learn/machine-learning) [Matlab/Octave]: A timeliness course on machine learning that covers fundamental concepts like basic linear algebra, regression, regularization, optimization, classification with SVMs, principal components analysis, and k-Means clustering. Note that this course does *not* use Python! I found that getting started in Octave (open-source alternative to Matlab) was easy and helped me grok linear algebra concepts in code more easily; Octave is [column-major](https://en.wikipedia.org/wiki/Row-_and_column-major_order) and 1-indexed (similar to Fortran, Julia, R, and matrix notation) whereas Numpy is row-major and 0-indexed (similar to C).


[**Fast.ai - Practical Deep Learning for Coders (Jeremy Howard)**](https://course.fast.ai/) [🐍🔥]:  Emphasis on practical applications rather than "bottom-up" theory. Excellent set of lectures that span deep learning, machine learning, and ethical AI. Be sure to check out the [2019 course](https://course19.fast.ai/) as well, which covers deep learning in slightly more detail but uses the deprecated v1 API of the `fastai` software. Some users might find the coding style overly terse and therefore difficult to understand.

[NYU - Deep Learning (Yann LeCun & Alfredo Canziani)](https://atcold.github.io/pytorch-Deep-Learning/) [🐍🔥]: A graduate-level second course in deep learning. A number of lessons go deep into active research topics, and I would recommend only picking the lessons/assignments that are of interest.

[Deep Learning Book (Ian Goodfellow, Yoshua Bengio, and Aaron Courville)](https://www.deeplearningbook.org/): A well-regarded deep learning text book published in 2016. Since the field is moving quite rapidly, much of the "Deep Learning Research" topics have advanced significantly since time of writing.

# Natural Language Processing (NLP)

[CMU 11-747 - Neural Nets for NLP (Graham Neubig)](https://www.youtube.com/playlist?list=PL8PYTP1V4I8CJ7nMxMC8aXv8WqKYwj-aJ): A series of graduate-level lectures on NLP and *not just transformers*.

[Advanced NLP with spaCy (Ines Montani)](https://course.spacy.io/en/): An interactive, four-part course spanning rule-based matching to neural networks, taught by one of the core developers of spaCy.

# Vision

[Stanford CS231n - Convolutional Neural Networks for Visual Recognition](https://cs231n.github.io/) [🐍🔥]: A very popular course that focuses on CNNs. Note that the final assignment also covers RNNs, Transformers, Saliency maps, GANs, LSTMs, and Self-Supervised Learning.
