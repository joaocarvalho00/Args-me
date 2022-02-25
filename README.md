# Args-me

https://www.args.me/index.html

Args-me is a search engine for arguments and about 2 years ago I was given acess to a dataset which contained a collection of arguments with respect to a certain topic and the relative stance of the argument with regard to the topic, as in the following example:

> Topic : "Contraceptive Forms for High School Students"

> Argument: "My opponent forfeited every round. None of my arguments were answered. I don\u2019t like the idea of winning by default, but here we are.Tule: it\u2019s good for students to get involved and address big issues like teen pregnancy. You need to be able to answer arguments like mine and not simply prepare for an abstinence-only type of response. You should also be aware that, in the U.S., condoms may be sold to minors in ANY state. A retailer who says it is illegal to sell you them is, frankly, wrong.

> Stance: "CON" ( CON = against and PRO = in favor )

I used this data to build a model that tried to predict the "stance" of an argument, which means I would feed the argumentative text to the model and it would make a prediction on if the text was in favor ( PRO ) or against ( CON ) the topic.

It was my first time utilizing these kind of tools so I tried to do a bit of everything, I started with scikit-learn and then moved on to tensorflow where I built a RNN and then started using GloVe embeddings and BERT.

This was a project to get a feel for the packages and try to have some hands-on experience as the only experience I had with this beforehand was doing some online courses on AI and Deep Learning.

If it's interesting for you, I remember I had around 65% accuracy even when increasing the complexity of the model, switching from simpler tree-based models to BERT the accuracy didn't change much, so maybe it needed more data or just a better processing of the data.

PS: I've added a "Logs" folder that has some accuracy and loss curves that I made at different stages of this project
