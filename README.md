<p align="center">
  <img src="lumbridge-mark.png" width="96" height="96" alt="Lumbridge">
</p>

# Lumbridge

**The open engine for agentic organizations.** Twelve open-source parts, mostly Rust, Apache-2.0.
They install on a standard Ubuntu machine and give every person and every agent in a company the same
terminals, mail, notes, library, voice and software factory, on machines you own.

The rule in every part: agents read, draft and build. A person sends, merges and does anything that can't be undone.
Every part that calls a model takes any OpenAI-compatible endpoint.

## The twelve parts

| Job | Part | What it does |
|---|---|---|
| 01 Sense | [lumbridge-voice](https://github.com/lumbridge-corp/lumbridge-voice) | Speech to text on your own hardware |
| 02 Think | [lumbridge-computer](https://github.com/lumbridge-corp/lumbridge-computer) | Serves, switches and watches open models on a GPU box you own |
| 03 Remember | [lumbridge-notes](https://github.com/lumbridge-corp/lumbridge-notes) | Markdown notes in the terminal, written by people and agents |
| 03 Remember | [lumbridge-library](https://github.com/lumbridge-corp/lumbridge-library) | A private library of documents, research, code and design systems |
| 04 Make | [lumbridge-factory](https://github.com/lumbridge-corp/lumbridge-factory) | Agents build each change in a sandbox; checks and a review gate it; a person merges |
| 05 Speak | [lumbridge-speak](https://github.com/lumbridge-corp/lumbridge-speak) | Text to speech on your own hardware |
| 06 Connect | [lumbridge-mail](https://github.com/lumbridge-corp/lumbridge-mail) | Agent-native mail client: agents draft, only a person sends |
| 06 Connect | [lumbridge-mobile](https://github.com/lumbridge-corp/lumbridge-mobile) | See what agents are doing and approve what waits for you, from a phone or the web |
| 07 Run | [lumbridge-core](https://github.com/lumbridge-corp/lumbridge-core) | The runtime on every machine: terminals that keep running |
| 07 Run | [lumbridge-app](https://github.com/lumbridge-corp/lumbridge-app) | The desktop workspace for terminals and agents |
| 07 Run | [lumbridge-tui](https://github.com/lumbridge-corp/lumbridge-tui) | The workspace inside any terminal |
| 07 Run | [lumbridge-mods](https://github.com/lumbridge-corp/lumbridge-mods) | Mods, layouts and keys for the App |

Start with **Core**. The App and the TUI are two ways to see your terminals; you need only one.

## Status

This is v0.1.0, and it is early. Every part builds from source; each README lists what it needs and what is not built yet.
We run all of it every day to run Lumbridge Corp. Interfaces can change until 1.0.

## Links

- Website and docs: [lumbridgecorp.com](https://lumbridgecorp.com) · [Guide: from a fresh Ubuntu machine](https://lumbridgecorp.com/guide/start)
- Open source, in plain words: [lumbridgecorp.com/open-source](https://lumbridgecorp.com/open-source)
- Questions and bugs: open an issue in the repo it concerns
- Security: do not open a public issue; email **security@lumbridgecorp.com** or use "Report a vulnerability" on the repo's Security tab
- Work with us: [lumbridgecorp.com/enterprise](https://lumbridgecorp.com/enterprise) · hello@lumbridgecorp.com · [@lumbridgecorp](https://x.com/lumbridgecorp)
