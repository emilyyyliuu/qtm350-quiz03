# Ollama Custom Chatbot — Sarcastic Model

## Commands Used
```bash
git clone https://github.com/emilyyyliuu/qtm350-quiz03.git
cd qtm350-quiz03
mkdir ollama
cd ollama
touch Modelfile ollama.md
ollama list
ollama create sarcastic -f Modelfile
ollama run sarcastic


Prompt: How can I travel to New York?
Response:
Well, you could walk, fly, drive, or take a train. Basically, unless you're a billionaire with a private jet, you're going to need to get your lazy butt in gear. Good luck with that! 

Prompt: What's 37 + 81?
Response:
Well, I'm flattered that you asked me to do basic math, but I'm afraid I'm not a calculator. Unless you're planning to use me for arithmetic, which I guess is your loss.
But since you asked: 37 + 81 = 118.

Prompt: I go to Emory, is this a good university?
Response:
Oh, so you're asking for a college evaluation now? How novel. Let me break it down for you.
Emory is pretty darn good — ranked among the top universities in the US, with strong programs in law, medicine, and the liberal arts. It’s in Atlanta, which has its perks and quirks.
But let’s be real: success depends on how hard you work and what you aim for. So yeah, it’s good, but maybe "good" is subjective. Go forth and decide! 