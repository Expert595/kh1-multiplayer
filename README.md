# KH1 Online Coop

Version: 0.9.5.

Requires your own copy of the game. Includes mod components and required replacement files, not a complete game installation.

## Installation and usage

Place `KH1OnlineCoop` inside the game folder beside `KINGDOM HEARTS FINAL MIX.exe`.

Run `1 - Setup.bat`, then `2 - Configure Online.bat`, then `3 - Start Online.bat`. The default listen port is 37171. Back up your saves before using this experimental build.

Version 0.9.5 is an experimental native second-Sora build. Player 1 can spawn a temporary duplicate; Player 2 remains network/read-only in the local isolation mode. The duplicate does not receive position, rotation, animation, or controller updates after spawning. This is not a finished playable two-Sora co-op release.

For the local mode, run `Local Test - Start Two Instances.bat`, follow the launch prompts, and load the same room in both instances.

## Changes in 0.9.5

- Added a temporary placement-table copy for one nested native Sora spawn on Player 1.
- Restored the original placement table immediately after the extra spawn call.
- Disabled post-spawn actor updates in the experimental duplicate mode.
- Retained the existing networking and two-instance foundation.
Support me on ko-fi if you like what I do. To help me.  https://ko-fi.com/arielmp
