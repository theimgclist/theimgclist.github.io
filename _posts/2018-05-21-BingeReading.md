---
title: Google Smart Compose, Machine Bias, Racist AI - Summarising One Night of Binge Reading from Blogs
hidden: true
---
<p align="center"><img src="/assets/images/bingereading.png"/></p>
<p align="center"><a href="https://www.forbesmiddleeast.com/en/artificial-intelligence-to-contribute-320-billion-to-the-middle-east-by-2030/">Pic Credit</a></p>  

After Sundar Pichai took the stage and started Google I/O 2018's keynote, I started to take a note of interesting things that were being announced and demoed. There were some very interesting demos and announcements, especially for those who are into Deep Learning. I was curious about Gmail's Smart Compose and Google Duplex besides other things, both of these being use cases of Natural Language Processing. Google Duplex got a lot of attention which was not surprising since the conversation made by Google Assistant with a real human sounded seamless and also human-like. If you are into Deep Learning, you would surely want to know at least a bit about how these are done and Google's Research blog is a good place to know more. And just in case you didn't know, ai.googleblog.com is Google's new research blog!  

We all are familiar with suggestions for word completion on phones. But why limit this feature to only word completion? Smart Compose is the new Gmail feature that helps in completing sentences by providing suggestions as we compose our emails. This too like many of the recent advancements and features, leverage neural networks. In a typical word completion task, the suggestive word is dependent on the prefix sequence of tokens/words. Depending on the previous words, the semantically closest word that could follow next is suggested. In the case of Smart Compose, in addition to the prefix sequence, the email header and also the previous email body(if present as in the case when the current mail is a response to an earlier mail) are considered as inputs to provide suggestions for sentence completion. 

<p align="center"><img src="https://2.bp.blogspot.com/-KlBuhzV_oFw/WvxP_OAkJ1I/AAAAAAAACu0/T0F6lFZl-2QpS0O7VBMhf8wkUPvnRaPIACLcBGAs/s640/image2.gif"/></p>
<p align="center"><a href="https://ai.googleblog.com/2018/05/smart-compose-using-neural-networks-to.html">Credit</a></p>  

Latency, scalability and privacy are three identified challenges that should be addressed to make this feature efficient, accessible and safe. For the sentence completion suggestions to be effective, the latency should be really less so that the user doesn't notice any delays. Considering that there are more than a billion people who use Gmail, it is quite hard to even imagine how different the context of each email would be. The model should be complex and scalable enough to accommodate as many users. Shouts of privacy are heard everywhere when any kind of data is involved. And there are only a few things that demand privacy more than our emails. The models therefore should not expose the users' data in any way.  
