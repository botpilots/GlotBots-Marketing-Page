Lately I’ve been reading research on how LLMs are performing in the translation industry. Mainly, I’ve focused on their entry and progress in the Workshop on Machine Translation (WMT) from 2023 to 2025, which could be considered the “Olympics” of machine translation.

Some insights I got (on a tangent or in addition to the ones in the video):
- The performance of the human translations is on a worrisome decline. This finding is to be taken seriously as WMT scores participants based on human evaluation metrics (human judging). The reason is because the rise of strong LLM-based MT systems is putting the quality bar higher, making it harder for human references to compete.
- Important to be cautious when a company boast about their automatic metric scores in WMT, since it does not necessary mean they were best on WMT's human evaluation metrics. This was the case for Unbabel's Tower70B model in WMT24 and for Tencent's Shy-hunyuan-MT in WMT25.
- LLM-based translations are generally inexpensive but can become very expensive if a frontier model is used without any restriction on reasoning (Gemini 2.5 Pro), even when translations are done on document-level with just one prompt. Tldr; "Brute-forcing" a frontier model to maximise quality is not preferred; a more careful approach on model choice and how to use it should be taken. 
- Reading the WMT23 paper, it was amazing to see how ChatGPT4 already at that time was challenging the top performing NMT-based systems, without even trying as an active participant. 
- At both WMT24 and WMT25, researchers were predominantly choosing the LLM-way (fine-tuning open weight models) as their strategy to maximise translation performance. Only three systems out of thirty six did not use LLMs in WMT25, and none of those ended up as top performers (in fact they weren't even included in the results section of the overview paper). 

Lastly, I'd like to add a bit more nuance to a statement I made in the beginning of the video, that "no ML research team can't beat any commercial LLMs":
- I made that statement after reading the results of WMT23, 24 and 25, where commercial LLMs were overall on top, beating the WMT-fine-tuned systems. 
- But why so? Because 1. their parameter count are huge, and 2. the research teams competing are limited in budget, time and by competition rules. 
- Still, the fact that a general AI system can beat a very sophisticated AI specifically trained for the task, is fascinating. It emphasises that the general commercial LLMs are not only systems of great intelligence, but also of great robustness. 

Happy to talk further about all this in the comment section!