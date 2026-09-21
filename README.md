# Cybersecurity write-ups

Articles, research notes, CTF write-ups and lab walkthroughs by Markus Walker.

**Read them at [markus-doc.github.io/cybersecurity-writeups](https://markus-doc.github.io/cybersecurity-writeups/).**
That is the formatted site, with navigation, backlinks and search. This repository is
the source and build scaffolding behind it, and is not the place to read anything.

Current series: a full crawl-through of the TryHackMe Red Team Capstone Challenge,
written as the work actually happened rather than as a tidy solution path, including
the dead ends.

More at [markuswalker.com](https://www.markuswalker.com/) and
[github.com/Markus-Doc](https://github.com/Markus-Doc).

## Layout

- `content/` holds the write-ups in Markdown. Everything worth reading is here.
- `quartz/`, `quartz.config.ts` and `quartz.layout.ts` are the static site generator.
- The site builds and deploys to GitHub Pages from `main` through a workflow.

## Credits and licence

The site is built on [Quartz v4](https://quartz.jzhao.xyz/) by Jacky Zhao, MIT
licensed, and the MIT licence in `LICENSE.txt` covers it. Quartz's own documentation
lives at [quartz.jzhao.xyz](https://quartz.jzhao.xyz/) and is the right reference for
how the generator works; it used to occupy this README, which meant visitors landed on
the generator's documentation rather than the write-ups.

The write-ups themselves are the author's own work. Training-platform content, lab
material, challenge artefacts and screenshots referenced in them remain the property
of their respective owners and are not relicensed here.
