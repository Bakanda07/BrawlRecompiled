# About this fork

This is a fork of [josiahg2502-glitch/BrawlRecompiled](https://github.com/josiahg2502-glitch/BrawlRecompiled), maintained by Bakanda07 as a continuation of the open-source project. It carries the upstream work as it stood on the date below.

- Game / target: Super Smash Bros. Brawl (Wii, PowerPC), built on WiiCompiled
- Licence: GPL-3.0. The licence file and the author notices of the upstream repository are kept as they are.
- Base commit: `a77be8847ec9d8cf6128f086fe9c493d105ecbce` (a77be88, 2026-10-31: "Release 0.5.3: notice mod hooks on a module's edge code pages (#19)")
- Base tag: `upstream-base-2026-11-07` marks that commit in this repository.
- Default branch: `master`

## What differs from upstream

2 commits on `master` that upstream does not have: the two commits of upstream pull request #35 (Libra2393, `rev2-support`: Brawl disc revision 2 support in the launcher, `game_folder.cpp` and `hle/storage/dvd.cpp`), fast-forwarded from the PR ref so authorship is preserved.

## Releases and mirrors

Release v0.5.3 is mirrored on this account, unchanged. Its launcher and updater still point at the upstream repository; they have not been repointed.

Releases published here before any change of ours are copies of the upstream builds. They are not built from this repository.

## Following upstream

```sh
git fetch upstream
git log --oneline master..upstream/master
git merge --ff-only upstream/master
```

## Rules for this fork

- No game data, keys, extracted files or code generated from a game goes into this repository.
- A release built from this fork must say so in its name or notes and give the base tag it started from.
- Changes of ours are listed in the section above when they are merged.
