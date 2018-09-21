## Representation Learning Introduction
In representation learning, features are extracted from unlabeled data by training a neural network on a secondary,supervised learning task.
A good representation is one that makes a subsequent learning task easier. The choice of representation will usually depend on the choice of the subsequent learning task
## Motivation of Represntation Learning
Algorithms that can extract features from unlabeled data to improve the performance of data-limited tasks 

## Greedy layer-wise pretraining
Its is called greedy because it is agreedy algo meaning that it optimizes each piece of the solution independently,one piece at a time, rather than jointly optimizing all pieces. It is called layer-wise because these independent pieces are the layers of the network. Speciﬁcally, greedy layer-wise pretraining proceeds one layer at a time, training the k-th layer while keeping the previous ones ﬁxed. It is called unsupervised because each layer is trained with an unsupervised representation learning algorithm. However, it is also called pretraining because it is supposed to be only a ﬁrst step before a joint training algorithm is applied to ﬁne-tune all thelayers together.


## Representation Learning: A Review and New Perspectives outlines
The paper  motivation is threefolded into:
 - Right objectives to learn good representations,
 - how do we compute these representations, 
 - What is the connection between representation learning, density estimation, and manifold learning
 ### WHY SHOULD WE CARE ABOUT LEARNING REPRESENTATIONS?

- **Speech Recognition and Signal Processing**:
Representation-learning algorithms have also been applied to music, substantially beating the state-of-the-art in polyphonic transcription

- **Object Recognition**:
Deep learning has moved from digits to object recognition in natural images, and the latest
breakthrough has been achieved on the ImageNet dataset4 bringing down the state-of-the-art error rate from 26.1% to 15.3%

- **Multi-Task and Transfer Learning, Domain Adaptation**:
Transfer learning is the ability of a learning algorithm to exploit commonalities between different learning tasks in order to share statistical strength, and transfer knowledge across tasks.Most impressive are the two transfer learning challenges held in 2011 and won by representation learning algorithms.
 ### WHAT MAKES A REPRESENTATION GOOD?
**Priors for Representation Learning in AI**
 One reason why explicitly dealing with representations is interesting is because they can be convenient to express many general priors about the world around us, i.e., priors that are not task-specific but would be likely to be useful for a learning machine to solve AI-tasks
 - Smoothness
 - A hierarchical organization of explanatory factors
 - Shared factors across tasks
 - Natural clustering
 - Temporal and spatial coherence
 - Sparsity
 
 ** Smoothness and the Curse of Dimensionality**
 Although smoothness can be a useful assumption, it is insufficient to deal with the curse of dimensionality, because the number of such wrinkles (ups and downs of the target function) may grow exponentially with the number of relevant interacting factors, when the data are represented in raw input space

 **Distributed representations**
 The generalization of clustering to distributed representations is multi-clustering, where either several clusterings take place in parallel or the same clustering is applied on different parts of the input, such as in the very popular hierarchical feature extraction for object recognition based on a histogram of cluster categories detected in different patches of an image.
 In a distributed representation, an exponentially large number of possible subsets of features or hidden units can be activated in response to a given input. In a single-layer model, each feature is typically associated with a preferred input direction, corresponding to a hyperplane in input space, and the code or representation associated with that input is precisely the pattern of activation


**Depth and abstraction**
Depth is a key aspect to representation learning strategies comes with some advantages
- deep architectures promote the re-use of features, and
- deep architectures can potentially lead to progressively more abstract features at higher layers of representations.


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
