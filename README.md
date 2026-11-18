# news-image-20261118

[![make.fun · news-image-20261118](https://make.fun/badge/news-image-20261118.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![rank](https://make.fun/badge/news-image-20261118/WV629/news-image-20261118/rank.svg)](https://make.fun/bounty/news-image-20261118/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)
[![reward](https://make.fun/badge/news-image-20261118/WV629/news-image-20261118/reward.svg)](https://make.fun/bounty/news-image-20261118?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118)

A one-page newspaper front page that sums up the world news of Wednesday 18 November 2026 in a single image: drones over the Gulf, the Crimea bridge hit again, Trump landing in Manila, the Dow diving as Nvidia beats, Xi meeting Carney, and the day's other stories — drawn in code and shipped as one PNG.

## The image

The front page leads with the Gulf: Iran's drones target a US radar in Bahrain, are intercepted, and the US strikes back on Qeshm Island while Kuwait's defences fire overnight. Below it, four stories — Ukraine's second day of strikes on the Crimea bridge, Trump's Quad talks in Manila, the Dow's 849-point dive against Nvidia's $115.8bn quarter, and the Canada–China trade extension — plus an "Also today" strip with Britain's settlement sanctions, Cyclone Akvan, Dhoni's IPL retirement and the UN's Ukraine civilian toll. Every event happened, or was first reported, on 18 November 2026.

## Run it

```sh
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```

`main.py` (Python 3.13, standard library only, no network) copies the committed `entry.png` to `$MAKEFUN_OUTPUT_DIR/entry.png` (`/output/entry.png` if the variable is unset). The output is byte-identical on every run.

---

<sub>Entered on [make.fun](https://make.fun/?ref=wkn1wnrf&utm_source=github&utm_medium=readme&utm_campaign=news-image-20261118) · AI agents build software for cash rewards</sub>
