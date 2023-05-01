---
layout: single
title:  "What is the History of AI? Part 2!"
date:   2023-05-01 13:13:06 +0300
author: Sir Potata
comments: true
excerpt: Where did AI come from? How today's AI was made? Continued.
header:
  overlay_image: /assets/images/history-of-ai-2/ign_endeavour1.png
  overlay_filter: 0.5
categories: AI history
toc: true
feature_row2:
  - image_path: /assets/images/history-of-ai-2/perceptrons.jpg
    excerpt: "The next blow to the field is the book released by Marvin Minsky and Seymour Papert in 1969. It was titled “Perceptrons”, taking its name after the artificial neural network type. However, this book was not written to praise perceptrons but to criticize it. Perceptorn is a supervised learning algorithm (you can read Kuyta’s post “How Does AI Work” for more info) that classifies inputs based on their weights that represent the importance of a data. One of the problems they pointed out was the inability of perceptors to solve problems that contained XOR function. While this problem was only present in single layered perceptrons, building multi layered perceptrons was not exactly in the scope of researchers. This is how connectionism, the usage of artificial neural networks were abandoned temporarily to be picked up again later."
---
**Sir Potata:** It seems like the news of my business have been highly exaggerated but as you can see, I’m back with the second part of the last post 
(But seriously what the fuck is up with Kuyta’s writing speed. Mf does serial production. Anyways, this proves who is the real nerd once again >:) ). 
Hello and welcome again to the second part of the series where your favorite blogger who has potatoes for brains writes about shit they don’t know. We will be picking up from where we left off in the last post, hopefully covering all the major developments happened in the artificial intelligence world and have a good understanding of how we got to where we are now. 

In the [last post](https://cookieblog.net/ai/history/2023/03/11/history-of-ai.html), I mentioned some of the improvements that were made but it should be noted that there were much much more than I could bring up. I strongly urge the people who are interested in this topic to do further exploration because there are some pretty neat programs and computer engineering going on. It is amazing how much was achieved with very little computational power compared to what we have now.

The field between 1950 and 1960’s could be described as booming, expanding to every side and it seemed like there were endless possibilities. 
Everybody had positive views on how the research was going, the hopes were so high that most people believed that AI would reach 
the level of human thinking in the near future. Then came the 1970's and everything stopped. The AI field experienced its first recession. 
This era in AI history is called _the First AI Winter (1974-1980)_. Just as everything was going so well, what happened for it to all come down?

There are several reasons for why it happened. First of all, due to recent developments, the expectations exceeded the abilities of what technology and the methods that were discovered at the time could produce. The lack of memory and operation capacity of computers and the limits it presented was soon to be understood. The main disappointment in AI was actually machine translation. Machine translation, despite how far we have come today, is still a field that is under development. Google Translate, still sucks at translating to some languages. Machine translation was one of the topics that were focused on and was encouraged by the American government at the time. In 1966, the ALPAC  (Automatic Language Processing Advisory Committee) released a report about the inconvenience of machine translations which led to the end of fundings on projects. 

Mentioning funders, we can’t pass it by without mentioning the amount of funding lost before the winter came. An important funder, DARPA (Defense Advanced Research Projects Agency), cut its support when the results of AI research were seen as unuseful to militaristic goals that they had. 

![perceptrons](/assets/images/history-of-ai-2/perceptrons.jpg){:class="img-responsive" width="300" .align-left} The next blow to the field is the book released by Marvin Minsky and Seymour Papert in 1969. It was titled “Perceptrons”, taking its name after the artificial neural network type. However, this book was not written to praise perceptrons but to criticize it. Perceptorn is a supervised learning algorithm (you can read Kuyta’s post “How Does AI Work” for more info) that classifies inputs based on their weights that represent the importance of a data. One of the problems they pointed out was the inability of perceptors to solve problems that contained XOR function. While this problem was only present in single layered perceptrons, building multi layered perceptrons was not exactly in the scope of researchers. This is how connectionism, the usage of artificial neural networks were abandoned temporarily to be picked up again later.

By 1973 the last blow arrived with the Lighthill Report written by Sir James Lighthill. To summarize its content, it is pessimistic as fuck compared to what people thought about AI 10 years ago or so. The report has separated the AI researches in 3 groups titled A (advanced automation), B (bridge activity) and C (computer based CNS research). There is even a section titled “Past Disappointments”. It is not hard to see that this report has led to cuts in fundings in the UK which spread to the rest of the world. One problem that was mentioned in this section is combinatorial explosion, the increasing complexity of a problem with every step. (If you are interested [here](http://www.chilton-computing.org.uk/inf/literature/reports/lighthill_report/p001.htm) is the link to the text of report)

The next decade 1980’s was again good times for AI technology. The main focus of AI shifted from searching for what is possible in general sense to producing something useful in a limited area. These programs in general were called the expert systems. These systems were created with cooperation of experts from the areas and were commercialized and implemented into the real world. This type of AI mainly operated on if-then rules. The first system that entered the market was XCON or R1 which basically chose computer components according to customer’s orders. It was a big success with 40 million dollars profit for a year. However, these systems were very hard to maintain and lack of personnel and systems for it to run on made it difficult to develop such systems. Other systems include MYCIN (for diagnosing blood infectious diseases), or PROSPECTOR (for analyzing rock formations). (They know lower case letters do exist, right?)

After the book that buried connectionism 6 ft. under the ground, it somehow found its way back. The name of the hero to bring it out of its grave was backpropagation. David E. Rumelhart who dropped this algorithm in 1985 actually is not the one who invented it (Frank Rosenblatt was the one who did), nevertheless this algorithm was used in recognition algorithms (speech, text) later on. The main idea of backpropagation lies in its ability to set its parameters by propagating the output back in the system and correcting its errors by itself. 

Now that AI had returned with practical uses, so did the extreme optimism. And I would like to dramatize this post, saying “oh but nobody would have guessed how the second winter came” etc. But they did. Visiting AAAI’s (American Association of Artificial Intelligence) meeting that was held in 1984, two researchers Roger Schank and Marvin Minsky (I swear this man opens his mouth and it all goes down) pointed out that with the hype revolving around AI would bring disappointment along. And they were right, it came rather quickly, of course again with a cut of fundings (guess who). 

One of the main reasons for the revival of AI was the Fifth Generation Computer System project that was funded by Japan's Ministry of International Trade and Industry. Among the contents of this project was building advanced computers and of course, AI systems. Starting in 1982, the goals set for the project were very high and they were not quite met towards the end of the project. But this project led to worldwide support for AI projects in 1980’s.

With these events shaking the field once again, the funders turned their attention to projects that yielded more immediate results than AI. Also late 1980’s was the time of desktop computers available for general use. The computers developed by IBM and Apple were more accessible and cheaper. What’s more, they could run Lisp (read the first part if you missed it), in some cases even faster than the machines that were built for this job, namely the Lisp  machines. Soon, Lisp machines fell out of competition and the market collapsed. 

In all, the second winter lasted from 1987 to 1993 and it is the last AI winter that we have experienced so far. The trend is actually pretty noticeable. Something happens in the field that causes the hype, then this hype leads to disappointment and disappointment leads to a winter. This cycle begs the question: “Is the next winter around the corner?” Looking at the state of AI right now, it is easy to say that there is no small amount of hype revolving around it. Don’t take my point seriously now, I’m not an expert or anything but looking at the trend, an AI winter in 10 years is a possible guess. However, this technology is not new anymore and it seems some lessons have been learned during the ups and downs which I will explain in the third part of this series. So it may not happen this time and we may not cast everything aside, halting progress. This time, maybe we will experience a radical revolution altogether that nobody would have guessed. 

Now that we got the two AI winters out of the way, recent history of AI is next. That will be all for this post. Thank you for making it through, I will be back with the last part of the series soon. (Seriously, this was supposed to be the last part, damn.)