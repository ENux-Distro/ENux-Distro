<div align="center">

# Emir YILDIRIM

**Linux distribution developer · Pianist**

[![DistroWatch](https://img.shields.io/badge/DistroWatch-listed-blue?style=flat-square&logo=linux&logoColor=white)](https://distrowatch.com/enux)
[![SourceForge](https://img.shields.io/badge/SourceForge-hosted-orange?style=flat-square&logo=sourceforge&logoColor=white)](https://sourceforge.net/projects/enux)
[![GitHub Org](https://img.shields.io/badge/GitHub-ENux--Distro-181717?style=flat-square&logo=github)](https://github.com/ENux-Distro)

</div> 

---

## About Me

Hi everyone, I'm Emir. I'm a Turk who builds Linux distributions and low-level systems software. My main project is **ENux**, a Debian-based hybrid meta-distribution with Bedrock Linux pre-integrated, making it the first Linux distro to ship with Bedrock pre-installed. ENux is listed on DistroWatch and hosted on both GitHub and SourceForge.

Beyond distro work, I write systems tooling in C, including a custom package manager, a replacement init system, and a minimal libc. I also play the piano in my free time.

---

## Projects

### ENux
> *The first Linux distribution to ship with Bedrock Linux pre-installed. and 15 package managers in the live environment*

A Debian-based hybrid meta-distribution that gives you access to packages from virtually any Linux distro simultaneously via Bedrock's `strata`. Features 15 package managers in the live environment, custom kernels and customized XFCE

- Pre-fetched Bedrock strata (~3 GB ISO)
- `brl fetch` works in chroot non-PID 1 environments via xattr workaround
- Kernel postinstall hook for automatic Secure Boot signing

[![ENux Repo](https://img.shields.io/badge/GitHub-ENux-181717?style=flat-square&logo=github)](https://github.com/ENux-Distro/ENux)

---

### init.c
> *C + x86\_64 ASM replacement for Bedrock Linux's shell-based init system.*

Dramatically reduces boot time by replacing Bedrock's shell init with a compiled binary. Addresses Bedrock's crossfs architecture directly. Recognized by Bedrock Linux's creator (paradigm) on Reddit, who noted `brl-repair` and `brl-enable` as targets for further optimization.

[![init.c Repo](https://img.shields.io/badge/GitHub-init.c-181717?style=flat-square&logo=github)](https://github.com/ENux-Distro/init.c)

---

### epm
> *A C-written package manager with a custom `.epm` package format.*

Mirror-based package downloading, install record tracking, and full `install` / `purge` / `sync` / `clean` command support. Built from scratch for ENux.

---

## Tech Stack

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![x86\_64 ASM](https://img.shields.io/badge/x86__64_ASM-grey?style=flat-square&logo=assemblyscript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)

---

## Star History of ENux

[![Star History Chart](https://api.star-history.com/chart?repos=ENux-Distro/ENux&type=date&legend=top-left)](https://www.star-history.com/?repos=ENux-Distro%2FENux&type=date&legend=top-left)

<!-- FOLLOWERS_LIST_START -->

### [My Most Famous Followers](https://github.com/Joe-Huber/my-most-followed-followers)

| Profile | Name | Followers |
|---|---|---|
| <img src='https://avatars.githubusercontent.com/u/95758601?v=4' width='30' height='30'> | [slipstream8125](https://github.com/slipstream8125) | 38 |
| <img src='https://avatars.githubusercontent.com/u/71213934?v=4' width='30' height='30'> | [txmu](https://github.com/txmu) | 14 |
| <img src='https://avatars.githubusercontent.com/u/74541097?v=4' width='30' height='30'> | [agusbs](https://github.com/agusbs) | 2 |
| <img src='https://avatars.githubusercontent.com/u/289202987?v=4' width='30' height='30'> | [cagancc5316-wq](https://github.com/cagancc5316-wq) | 1 |

*Last updated: 2026-07-09 01:45:47 UTC*
<!-- FOLLOWERS_LIST_END -->

## GitHub Stats

<div align="center">

![ENux-Distro's GitHub stats](https://github-readme-stats.vercel.app/api?username=ENux-Distro&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ENux-Distro&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff)

</div>

---

<div align="center">
<sub>Why use one, when you can use them all</sub>
<sub>                                     - A wise man</sub>
</div>
