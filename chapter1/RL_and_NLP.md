### 1.1 Motivation

-  Machine learning address the problem of automatically learning computer programs from data.

​	  		**Machine Learning = Representation + Objective + Optimization**

- Representation learning aims to learn informative representation of objects from raw data automatically.

- Deep learning is a typical approach for representation learning. 

- Deep learning has two distinguishing features:

  - **Distributed Representation**: represent each object with a low-dimensional real-valued dense vector.  

  > one-hot representation in conventional representation schemes.

  - **Deep Architecture**: Deep learning algorithms usually learn a *hierarchical deep architecture* to represent objects, known as multilayer neural networks. 

### 1.2 The Importance of Representation Learning for NLP

- Natural language texts  with multiple granularities, multiple tasks, and multiple domains

  - **Multiple Granularities:**  NLP concerns about multiple levels of language entries (characters, words,....). Representation learning can represent the semantics of these language entries in a unified semantic space, and build complex semantic relations among these language entries.

  - **Multiple Tasks:** Various NLP tasks based on the same input. (given a sentence , Task: word segmentation, named entity recognition, relation extraction....). It will be more efficient and robust to build a unified representation space of inputs for multiple task.

  - **Multiple Domains:** Natural language texts may be generated from multiple domains (new articles, scientific articles,...). Regard texts in different language as multiple domains. Representation learning enables us build representations automatically from large-scale domain data.

    > Conventional NLP systems have to design specific feature extraction algorithms for each domain according to its characteristics.

### 1.3 Basic Ideas of Representation Learning

- All objects are projected into a unified low-dimensional semantic space.
- The geometric distance between two objects in the semantic space indicates their semantic relatedness;
- It is the relative closeness with other objects that reveals an object's meaning rather than the absolute position.

### 1.4 Development of Representation Learning for NLP

![image-20211125151511015](C:\Users\wsco74\AppData\Roaming\Typora\typora-user-images\image-20211125151511015.png)

### 1.5 Learning Approaches to Representation Learning for NLP

- **Statistical Features**: semantic representation for NLP in the early stage often come from statistics.

> Elements in representation are frequencies or numbers of occurrences of the corresponding entries counted in large-scale corpora.

- **Hard-craft Features:** gitStu