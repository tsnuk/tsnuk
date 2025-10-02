# I Built an AI Multimodal Stock-Price-Prediction System from Scratch by Watching YouTube Videos, Now I'm Open-Sourcing It.
## This Was My Journey

**Project Name:** [trade-AId-multimodal-transformer](https://github.com/tsnuk/trade-AId-multimodal-transformer)

I have over 20 years of experience in financial markets and equity trading (including founding an algorithmic trading company and serving as its head of algorithm development), but I had absolutely no experience in AI, ML, or Python.

When LLMs stormed into our lives, I had a realization: the same architecture used for training a language model, could be used to train on stock-price data with the objective of predicting future stock prices.

So, knowing nothing about AI (besides the occasional use of a chatbot), I set out on a self-learning mission to educate myself enough to build my own AI-based stock-price prediction system.

Amazingly, I found that YouTube has incredible content on anything related to AI, at any level of depth desired (thank you Luis Serrano! I really loved your videos on AI. Your ability to take complex concepts and turn them into simple, easy-to-digest narratives, is unparalleled!).

And so, there I was learning AI architecture: transformers, neural networks, and with every subject learned, new ones emerged: everything from gradient descent, loss, and backpropagation to positional embeddings, softmax, and activation functions, and of course, attention.

Initially, I did not know about cross-attention or multimodal architecture, and so the first system I built was single modality. But later, as the need arose for combining price data with timestamps, volume, VIX, various indicators, or even other stocks' price data, I learned of the existence of the multimodal model, and transitioned the system into that architecture.

Next, I needed to perfect my (non-existent) Python writing skills, so… back to YouTube. Yes, the platform has great content on Python too, and with that, I was able to move from theory (watching videos on AI) to practice (building an AI system)... by watching more videos :). And special thanks to David Langer, who has a great series on Python. I loved how laid-back, yet thorough you are in those videos. It was a pleasure learning Python with you!

This brought me to the very advanced level of beginner level in Python. But that worked fine because most of the code-writing heavy lifting was to be handled by Gemini and Claude Code, allowing me to grow my Python skills alongside them (I can testify these are truly magical, sorcery-making tools that made this project possible).

But first, there was one more important video to watch before I got started. The final video that put it all together for me was a 2-hour video (I watched it twice) of building GPT from scratch by Andrej Karpathy. I am particularly grateful to Andrej for showing me that this is in fact doable and that anyone who wants to can build such a system.

And with that, I was ready to start building my system… About 9 months after watching the first video, I had my multimodal stock prediction system complete and running.

After testing the system for a while on various financial data, I was not able to produce the results I hoped for - the system's predictions did not consistently achieve the profitability I required for live trading. I do however know that there's no limit to the types of data (equities, commodities, currencies,…) that can be trained using this system, and since I cannot possibly examine all those different avenues, I'm open-sourcing the system for anyone interested in using it.

Configure the system as you wish (I included readme docs as well as run and setup examples), use your own data (any time-series data, not restricted to financial data), or even further develop the system yourself. Hopefully, you will be able to make good use of it.

---

## The Project
[trade-AId-multimodal-transformer](https://github.com/tsnuk/trade-AId-multimodal-transformer)

## Connect
[LinkedIn](https://www.linkedin.com/in/tahl-salomon-1881391a/)
