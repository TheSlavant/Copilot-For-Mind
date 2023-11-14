# Tolstoi: Copilot for mind

My Twitter: [@TheSlavant](https://twitter.com/TheSlavant)

_Note: Tolstoi is a quick weekend project that I made for myself. While it is fun to play with, it is far from being fully reliable for now. If you're interested in making it better, [let me know!](https://twitter.com/TheSlavant)_

Tolstoi is a tool that helps you think better. It uses your journals to learn about you and acts as a trusted advisor when you make new entries in your journal. 

Features:
* Check if your thoughts today align with your long-term values.
* Point out if you're stuck on the same though.
* Make sure you don't fall for cognitive biases.

### Quick Start

1. Go to `data/advisor` and replace `demo_journal.txt` with your journal entries.
2. Run python `advisor.py`.
3. Write down your thoughts in a few sentences and hit Enter.

The first time you run `advisor.py`, it will build an index from your journal. On subsequent runs, you can comment out the line that builds the index ( `index = build_index("data/advisor")` ) to save time and money.


### Examples

To generate public examples, I asked GPT-4 to write journal entries for a fictional male in his 20s. You can access the source file in `data/advisor`.

**I'm considering taking the next step in my career.**

![FsaQr1zaQAARU5a](https://github.com/YaroslavShipilov/copilot-for-mind/assets/17534053/2db6a286-eabc-4ede-9868-7f35a52bb2cb)

**Has anything been bothering me lately that i hinted at more than once?**

![FsaQrAhaIAAkNoe](https://github.com/YaroslavShipilov/copilot-for-mind/assets/17534053/84209534-e2d5-46a6-b26a-5077817ffb93)

Also worked well for:
* What are my long-term values?
* I'm thinking about making decision X
* I'm sad/happy/bored/anxious/grateful
