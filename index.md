## Representation Learning Introduction
In representation learning, features are extracted from unlabeled data by training a neural network on a secondary,supervised learning task.
A good representation is one that makes a subsequent learning task easier. The choice of representation will usually depend on the choice of the subsequent learning task
## Motivation of Represntation Learning
Algorithms that can extract features from unlabeled data to improve the performance of data-limited tasks 

## Greedy layer-wise pretraining
its is called greedy because it is agreedy algo meaning that it optimizes each piece of the solution independently,one piece at a time, rather than jointly optimizing all pieces. It is called layer-wise because these independent pieces are the layers of the network. Speciﬁcally, greedy layer-wise pretraining proceeds one layer at a time, training the k-th layer while keeping the previous ones ﬁxed. It is called unsupervised because each layer is trained with an unsupervised representation learning algorithm. However, it is also called pretraining because it is supposed to be only a ﬁrst step before a joint training algorithm is applied to ﬁne-tune all thelayers together.


## Representation Learning: A Review and New Perspectives outlines
The paper  motivation is threefold:
 -Right objectives to learn good representations,
 -how do we compute these representations, 
 -What is the connection between representation learning, density estimation, and manifold learning
Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/rohit46666/Rohit-Chaudhary.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
