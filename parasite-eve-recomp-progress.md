### Parasite Eve Recomp — progress update

I've been working on a native recompilation of the PlayStation version of *Parasite Eve* with PSXRecomp. Both discs are registered in one project. They contain the same boot program, so the recomp uses one generated game build and lets me select a disc before starting.

The first build compiled, booted, and reached early gameplay. Since then, I've built and launched a native version on a test device. The controller now works in both the launcher and the game. FMV playback looks crisp, and higher internal rendering resolution has made the character models look noticeably better. Earlier testing on another test device showed occasional stutters in FMV audio, so audio still needs a longer check.

This is still an early playthrough. I need to reach a save point, confirm that saving and loading work, and test more of the game. Both discs are set up to use the same memory-card location, but I have not yet verified loading a save across them. The main remaining hurdle is the in-game handoff from Disc 1 to Disc 2: selecting either disc at launch works, while swapping discs during a running session has not been implemented or tested.

The goal is a reliable two-disc playthrough, including the later content, with a smooth disc transition. For now, this is a local work-in-progress project with no repository or release.
