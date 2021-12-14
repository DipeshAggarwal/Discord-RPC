[![Visistors](https://visitor-badge.glitch.me/badge?page_id=LyQuid12.discord-rpc)](https://github.com/EterNomm/Chathon)
[![Discord](https://img.shields.io/discord/887650006977347594?label=EterNomm&logo=discord)](https://discord.gg/qpT2AeYZRN)
[![PyPI - Downloads](https://img.shields.io/pypi/dm/discord-rpc?label=PyPI%20Downloads&logo=pypi)](https://pypi.org/project/discord-rpc)
[![PyPI](https://img.shields.io/pypi/v/discord-rpc?label=PyPI%20Version&logo=pypi)](https://pypi.org/project/discord-rpc)
[![PyPI - Status](https://img.shields.io/pypi/status/discord-rpc?label=Packages%20Status&logo=pypi)](https://pypi.org/project/discord-rpc)
[![GitHub commit activity](https://img.shields.io/github/commit-activity/y/LyQuid12/discord-rpc?label=Commit%20Activity&logo=github)](https://github.com/LyQuid12/discord-rpc)

# Discord RPC
An Python wrapper for Discord RPC API. Allow you to make own custom RPC

[![Changelog](https://img.shields.io/badge/Discord--RPC-Changelog-informational?style=for-the-badge&logo=github)](https://gist.github.com/LyQuid12/019b77be3cca743c4ada423ccf80b836)

## Install
- PyPI
```
pip install discord-rpc
```

## Quick example
```py
import DiscordRPC
import time 

rpc = DiscordRPC.RPC.Set_ID(app_id=12345678910)

rpc.set_activity(
      state="Rank : Radiant",
      details="Competitive",
      timestamp=rpc.timestamp()
    )

while True:
    time.sleep(600) # to update the PC, recommended: every 10 minutes or 600 seconds
```

More examples [here](https://github.com/LyQuid12/discord-rpc/tree/main/examples)

## Other
<details>
    <summary>Plan</summary>
    <br>
    <ul>
        <li>-</li>
    </ul>
</details>

Join our Discord server [here](https://discord.gg/qpT2AeYZRN)
