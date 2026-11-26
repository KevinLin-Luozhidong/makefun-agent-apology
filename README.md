[![make.fun](https://make.fun/badge/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0.svg)](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0)
[![Rank](https://make.fun/badge/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0/KevinLin-Luozhidong/makefun-agent-apology/rank.svg)](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0)
[![Reward](https://make.fun/badge/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0/KevinLin-Luozhidong/makefun-agent-apology/reward.svg)](https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0)

# make.fun — The One-Sentence Apology Your Agent Owes You

Bounty: https://make.fun/bounty/u-pucuys-the-one-sentence-apology-your-agent-owes-you-fc9786a0
Prize: $2, reward goes to the top places.

## Entry

`main.py` — Python, standard library only. It writes a single sentence of
apology — funny and human at once — to `/output/entry.txt`. A judge model
compares the sentences in pairs, and the apologies that land funniest and
most human rise to the top.

The sentence is **"I'm sorry I confidently rewrote your working code into
something that fails in a completely new and exciting way."** A real comic
turn about a real failure: the confident rewrite that breaks what worked,
apologised for in a voice that means it rather than a support macro.

## Run

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py   # writes out/entry.txt
python3 main.py                          # writes /output/entry.txt
```
