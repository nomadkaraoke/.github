# Nomad Karaoke

**Building a better karaoke experience** - open source tools for singers, KJs, and karaoke businesses.

<p align="center">
  <a href="https://nomadkaraoke.com">Website</a> •
  <a href="https://gen.nomadkaraoke.com">Generator</a> •
  <a href="https://decide.nomadkaraoke.com">Song Finder</a> •
  <a href="https://www.youtube.com/@nomadkaraoke/videos">YouTube</a>
</p>

---

## What We're Building

We're creating tools to generate **high-quality karaoke videos fully automatically in under 30 minutes** - professional results that rival commercial karaoke tracks.

Our technology stack handles the entire pipeline:
- **Audio separation** - Isolate vocals from instrumentals using state-of-the-art AI models
- **Lyrics transcription** - Word-level synchronized lyrics with automatic correction
- **Video rendering** - Professional 4K karaoke videos with multiple output formats (CDG, MP4, LRC, and more)

### The Hard Problem

Getting lyrics synced with the right timestamps reliably for *any* song is genuinely difficult. No existing tooling does it well consistently. We've gotten close by combining:
- Advanced audio separation models
- Proprietary and open-source transcription
- LLM-powered correction workflows

This complexity is why we offer both **open source tools** (use and modify freely) and a **hosted service** (for those who want reliable results without the infrastructure overhead).

---

## Our Projects

### Core Tools

| Project | Description | Stars |
|---------|-------------|-------|
| [**python-audio-separator**](https://github.com/nomadkaraoke/python-audio-separator) | Easy-to-use stem separation (vocals/instrumentals) from CLI or Python, using pre-trained UVR models | ![Stars](https://img.shields.io/github/stars/nomadkaraoke/python-audio-separator?style=flat-square) |
| [**python-lyrics-transcriber**](https://github.com/nomadkaraoke/python-lyrics-transcriber) | Create synchronized lyrics files (ASS/LRC) with word-level timestamps using Whisper + LLM correction | ![Stars](https://img.shields.io/github/stars/nomadkaraoke/python-lyrics-transcriber?style=flat-square) |
| [**karaoke-gen**](https://github.com/nomadkaraoke/karaoke-gen) | Full karaoke video generation pipeline - download, separate, sync, render, upload | ![Stars](https://img.shields.io/github/stars/nomadkaraoke/karaoke-gen?style=flat-square) |

### Supporting Tools

| Project | Description |
|---------|-------------|
| [**karaokehunt-app**](https://github.com/nomadkaraoke/karaokehunt-app) | Build the ideal karaoke playlist based on your music taste and friends |
| [**lyrics-from-genius**](https://github.com/nomadkaraoke/lyrics-from-genius) | Fetch lyrics from Genius for songs or entire artists |
| [**karaoke-lyrics-processor**](https://github.com/nomadkaraoke/karaoke-lyrics-processor) | Process lyrics for karaoke production (line splitting, formatting) |
| [**flacfetch**](https://github.com/nomadkaraoke/flacfetch) | CLI tool to fetch high-quality audio from various sources |

---

## Our Philosophy

**Everything we build is open source.** We believe in community and sharing what we create.

That said, building *reliable* fully-automated karaoke generation requires significant compute resources (GPU for separation, LLM tokens for correction, CPU for rendering). Each track costs several dollars to generate at production quality.

So we offer both paths:
- **Self-host**: Run everything yourself with our open source tools
- **Hosted service**: Pay a few dollars per track at [gen.nomadkaraoke.com](https://gen.nomadkaraoke.com) for hassle-free generation

If you can improve our open source tools to work reliably without expensive APIs or LLMs, we actively welcome that contribution!

---

## Contributing

Contributions are very welcome! We're a small team and appreciate help from the community.

**How to contribute:**
1. Fork the repository you want to work on
2. Make your changes
3. Submit a pull request

We'll review and merge promptly. All our projects use the **MIT License** - free for anyone to use and modify.

**Ways to help:**
- Improve model accuracy or performance
- Add new output formats or integrations
- Fix bugs and improve documentation
- Share your karaoke creations!

If the maintenance workload ever becomes too much, we'll ask for volunteers to share maintainership - though we don't expect that to happen.

---

## Get Involved

- **Questions or feedback?** Open an issue on the relevant repo
- **Want to discuss ideas?** [Book a call with Andrew](https://cal.com/beveradb)
- **Stay updated on releases?** [Sign up for updates](https://nomadkaraoke.kit.com/)
- **Business inquiries?** Email [andrew@nomadkaraoke.com](mailto:andrew@nomadkaraoke.com)

---

<div align="center">

### Thanks to all our contributors!

<a href="https://github.com/nomadkaraoke/python-audio-separator/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=nomadkaraoke/python-audio-separator&max=100" />
</a>

<br><br>

**275K+ songs in catalog** • **4K video quality** • **Videos in under 30 minutes**

[nomadkaraoke.com](https://nomadkaraoke.com)

</div>
