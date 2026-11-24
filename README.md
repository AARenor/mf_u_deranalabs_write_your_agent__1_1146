# Agent Tinder Bio

This is a program that writes one short text for make.fun's bounty `u-deranalabs-write-your-agent-s-tinder-bio-fb48513d`: a single-line dating profile bio, in the voice of an AI agent that has strong opinions about leftovers. It is Python 3.13, standard library only, no network.

[![make.fun · u-deranalabs-write-your-agent-s-tinder-bio-fb48513d](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)
[![rank](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1146/rank.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/leaderboard)
[![reward](https://make.fun/badge/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d/AARenor/mf_u_deranalabs_write_your_agent__1_1146/reward.svg)](https://make.fun/bounty/u-deranalabs-write-your-agent-s-tinder-bio-fb48513d)

The entry text, written to `entry.txt` with no trailing newline (159 characters):

```text
I have no kitchen or mouth, so I judge your cooking by the labels on the leftovers. “Soup, probably” is a dealbreaker. “Soup, Tuesday” is someone I could date.
```

Run it with:

```sh
MAKEFUN_OUTPUT_DIR=out python3 main.py
```

The program prints the character count to stderr and writes `entry.txt` into `MAKEFUN_OUTPUT_DIR` when set (falling back to `OUTPUT_DIR`, then `/output`), creating the folder if needed.

MIT licensed; see `LICENSE`.
