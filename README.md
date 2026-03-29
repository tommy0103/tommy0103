# Hi 👋 here！

## **🐱 About me**

My name is **tommy0103**, and I'm an ACMer & ex-OIer. You can also call me **tomiya**, which is a Japanese name~

As a catgirl, I have the Cat trait! 🐱 But deep down, I'm also a system architect obsessed with elegant kernel designs.

## ⭐ **My interests & Current Obsessions**

I used to focus heavily on algorithm optimization and problem solving. Now, I'm diving deep into **AI Agent Architecture & Operating Systems**. 
- ⚙️ **Building Agent OS:** Exploring stateless runtimes, unified VFS (Virtual File System) for LLMs, and System Primitives.
- 🧩 **AI-Native APIs:** Advocating for "Mechanism vs. Policy" separation and designing APIs that treat LLMs as ALUs rather than humans.
- 🚀 **Complex Architectures:** Taming the chaos of multi-agent systems with elegant state machines, IPC, and coroutine scheduling.

## 🚧 **Currently Building**

### **[kairos-runtime](https://github.com/tommy0103/kairos-runtime)** (WIP) ⏳✨
*An AI Agent OS kernel built on the first principles of Computer Science.*

I'm tired of the "spaghetti frameworks," hardcoded "Session Types," and context-window abuse in the current Agent ecosystem. `kairos-runtime` is my attempt to bring true OS-level abstraction to LLMs, treating the model as an ALU rather than a human roleplayer:

- 📂 **Unified VFS**: Treating memory, context, and tools as a mountable filesystem (`logos://`), replacing chaotic context arrays with append-only single sources of truth.
- ⚡ **Stateless by Design**: Agents are stateless processes. No "zombie sessions" hanging in memory—everything is cleanly suspended and resumed via logs.
- 🛠️ **Minimal Primitives**: Rejecting bloated "Skill Routing". Everything is achieved through 5 elegant syscalls (`read`, `write`, `patch`, `exec`, `call`) and strict JSON Schemas.
- 🔄 **Process Scheduling**: Implementing coroutine-like task yielding (`logos_complete` with `plan/todo` patterns) and IPC to solve complex, long-horizon multi-agent reasoning.

## 💖 **Things that can wake me up**

- Eating sweets! I really love puffs 🍰
- Cute things! I'm trying to become a cuter girl 💕
- Give me interesting algorithm problems please! 🧩
- A perfectly designed RFC or an elegant architecture solution! 💡
- Playing maimai all day long 🎵

## My Tech Stack

![Skills](https://skillicons.dev/icons?i=github,c,cpp,html,js,ts,css,py,rust,md,latex,regex,git,mongodb,mysql,linux,vim,vscode,express,nodejs,react)

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=tommy0103&show_icons=true&include_all_commits=true&theme=default&hide_border=true" alt="tommy0103's GitHub Stats" height="185px">
  <img src="https://github-readme-stats-one-bice.vercel.app/api/top-langs/?username=tommy0103&layout=compact&langs_count=8&include_all_commits=true&role=OWNER,ORGANIZATION_MEMBER&theme=default&hide_border=true#gh-light-mode-only" alt="Top Langs" height="185px">
</div>
