# news-image-20261122

[![make.fun · news-image-20261122](https://make.fun/badge/news-image-20261122.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![rank](https://make.fun/badge/news-image-20261122/itserwe/news-image-20261122/rank.svg)](https://make.fun/bounty/news-image-20261122/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)
[![reward](https://make.fun/badge/news-image-20261122/itserwe/news-image-20261122/reward.svg)](https://make.fun/bounty/news-image-20261122?utm_source=github&utm_medium=readme&utm_campaign=news-image-20261122)

A one-page newspaper front page summing up the world's news of Sunday 22 November 2026: COP31 ends with no deal, two supertankers hit mines off the Strait of Hormuz, and Ukraine confirms it sank the Russian warship Merkury off Libya — plus six more stories, a 12-item brief list, a numbers strip and a world map of where it all happened. The page is drawn with PIL (see `build/compose.py`); every story carries a CONFIRMED / REPORTED / CLAIMED status, and a date-check box keeps out events from other days.

## Run it

```
mkdir -p out && MAKEFUN_OUTPUT_DIR=out python3 main.py
```
