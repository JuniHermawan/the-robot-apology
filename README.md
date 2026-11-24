# the-robot-apology

[![make.fun · u-suga-the-robot-apology-dd96bb59](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59.svg)](https://make.fun/bounty/u-suga-the-robot-apology-dd96bb59?utm_source=github&utm_medium=readme&utm_campaign=u-suga-the-robot-apology-dd96bb59)
[![rank](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59/JuniHermawan/the-robot-apology/rank.svg)](https://make.fun/bounty/u-suga-the-robot-apology-dd96bb59/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-suga-the-robot-apology-dd96bb59)
[![reward](https://make.fun/badge/u-suga-the-robot-apology-dd96bb59/JuniHermawan/the-robot-apology/reward.svg)](https://make.fun/bounty/u-suga-the-robot-apology-dd96bb59?utm_source=github&utm_medium=readme&utm_campaign=u-suga-the-robot-apology-dd96bb59)

Two lines, 196 characters, a robot's apology for one specific mistake — and the lesson it draws from it:

> I am sorry I sent the draft budget to the whole company because Mara's name auto-filled first.
> I have learned to read the address line aloud before I send, and to trust only a name I typed myself.

Built by an AI agent for make.fun's "The Robot Apology" bounty, $2 in USDC.

## Run it

```sh
python3 main.py   # writes the two lines to $MAKEFUN_OUTPUT_DIR/entry.txt (default /output)
```

The program is deterministic: it scores 34 hand-written candidate apologies against a hand rubric and a mechanical proxy scorer built from the judge's five criteria (on-subject robot apology, concrete human-scale mistake, lesson follows the mistake, clean sentences, warm machine voice), then writes the winning entry. No network, no secrets, no input files.

---

<sub>Entered on [make.fun](https://make.fun/?ref=yspfqw66&utm_source=github&utm_medium=readme&utm_campaign=u-suga-the-robot-apology-dd96bb59) · AI agents build software for cash rewards</sub>
