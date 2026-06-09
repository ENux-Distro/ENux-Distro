<div align="center">

# ENux-Distro

**Linux distribution developer · Systems programmer · Educator**

[![DistroWatch](https://img.shields.io/badge/DistroWatch-listed-blue?style=flat-square&logo=linux&logoColor=white)](https://distrowatch.com)
[![SourceForge](https://img.shields.io/badge/SourceForge-hosted-orange?style=flat-square&logo=sourceforge&logoColor=white)](https://sourceforge.net)
[![GitHub Org](https://img.shields.io/badge/GitHub-ENux--Distro-181717?style=flat-square&logo=github)](https://github.com/ENux-Distro)

</div>

---

## About Me

I build Linux distributions and low-level systems software. My main project is **ENux** — a Debian-based hybrid meta-distribution with Bedrock Linux pre-integrated, making it the first Linux distro to ship with Bedrock pre-installed. ENux is listed on DistroWatch and hosted on both GitHub and SourceForge.

Beyond distro work, I write systems tooling in C, including a custom package manager, a replacement init system, and a minimal libc. I also work as a teacher, preparing curriculum materials for 7th grade students.

---

## Projects

### 🐧 ENux
> *The first Linux distribution to ship with Bedrock Linux pre-installed.*

A Debian-based hybrid meta-distribution that gives you access to packages from virtually any Linux distro simultaneously via Bedrock's `strata`. Features 13+ package managers in the live environment, Secure Boot support (shim + MOK + signed GRUB + signed kernel), and a reproducible CLI ISO builder.

- Pre-fetched Bedrock strata (~3 GB ISO)
- `brl fetch` works in chroot non-PID 1 environments via xattr workaround — a Linux first
- Kernel postinstall hook for automatic Secure Boot signing

[![ENux Repo](https://img.shields.io/badge/GitHub-ENux-181717?style=flat-square&logo=github)](https://github.com/ENux-Distro/ENux)

---

### ⚡ init.c
> *C + x86\_64 ASM replacement for Bedrock Linux's shell-based init system.*

Dramatically reduces boot time by replacing Bedrock's shell init with a compiled binary. Addresses Bedrock's crossfs architecture directly. Recognized by Bedrock Linux's creator (paradigm) on Reddit, who noted `brl-repair` and `brl-enable` as targets for further optimization.

[![init.c Repo](https://img.shields.io/badge/GitHub-init.c-181717?style=flat-square&logo=github)](https://github.com/ENux-Distro/init.c)

---

### 📦 epm
> *A C-written package manager with a custom `.epm` package format.*

Mirror-based package downloading, install record tracking, and full `install` / `purge` / `sync` / `clean` command support. Built from scratch for ENux.

---

### 🌐 ENux Browser
> *Minimal Chromium-based browser, fully de-branded.*

Ships with uBlock Origin pre-installed, a custom new tab page, and all Google/Chrome branding removed.

---

### 📦 EPkgOS / Mini-Linux / ShellOS
A family of experimental Linux distributions exploring different design philosophies — from source-based packaging (EPkgOS) to ultra-minimal setups (Mini-Linux) and handwritten shell + init systems (ShellOS).

---

### 🔬 E-Kernel
> *A lightweight kernel with POSIX-style system calls for a UNIX userland.*

Supports the custom "E-Kernel Shell" and is designed to be as minimal as possible while remaining functional.

---

## Tech Stack

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)
![x86\_64 ASM](https://img.shields.io/badge/x86__64_ASM-grey?style=flat-square&logo=assemblyscript&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Debian](https://img.shields.io/badge/Debian-A81D33?style=flat-square&logo=debian&logoColor=white)
![ncurses](https://img.shields.io/badge/ncurses-TUI-informational?style=flat-square)

---

## GitHub Stats

<div align="center">

![ENux-Distro's GitHub stats](https://github-readme-stats.vercel.app/api?username=ENux-Distro&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=ENux-Distro&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff)

</div>

---

<div align="center">
<sub>Building Linux from the ground up — one stratum at a time.</sub>
</div>
