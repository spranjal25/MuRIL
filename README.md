# MurRIL - Profanity classification for Dravidian Languages

[MuRIL: Multilingual Representations for Indian Languages](https://arxiv.org/abs/2103.10730) is a BERT based model retrained on the Embeddings of Indian Languages like Hindi, Tamil, Kannada etc.

This repository walks you through the processes involved in fine tuning an NLP model for task specific applications using [Transformers](https://huggingface.co/google/muril-base-cased) (:hugs:) implementation. We will deal with a hate-speech classification task in this one. But remember, You can always generalise it to any number of classes (as long as you can procure the right dataset :grinning:) just y adjusting the number of outputs in the final layer.

**TASK** : A six-class classification problem based on Tamil, Kannada and Malayalam language tweets (credits: [ACL](https://www.aclweb.org/portal/content/first-workshop-speech-and-language-technologies-dravidian-languages-eacl-2021)). 

Class Labels: 
<ul>
<li> 'Not_offensive'</li>
<li> 'Offensive_Targeted_Insult_Group'</li>
<li> 'Offensive_Targeted_Insult_Individual'</li>
<li> 'Offensive_Targeted_Insult_Other'</li>
<li> <'Offensive_Untargeted'</li>
<li>'Not {language_name}'</li>
</ul>

#### You could dive right into the colab notebook!
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1A-wsUPLXPwrhX9JgYqBmwJYyyzpu8zGc?usp=sharing)

> **_NOTE:_**  You might want to make a copy of the notebook first.

### Or, you could come along to know more!
> *What do we need?* 
> 1.  A basic Understanding of **How BERT works?** ([Insightful: Article](https://www.analyticsvidhya.com/blog/2021/06/a-gentle-introduction-to-muril-multilingual-representations-for-indian-languages/))
> 2. Understanding of tokenizers and word embeddings.
> 3. PyTorch framework. 

*Click the icon to know more about PyTorch and how it works*

[![](https://www.vectorlogo.zone/logos/pytorch/pytorch-ar21.svg)](https://pytorch.org/)
