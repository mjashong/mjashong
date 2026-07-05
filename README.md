<!-- This file lives in a repo named exactly `mjashong/mjashong` and renders on github.com/mjashong -->

# Hi, I'm Michael J. Ashong 👋

**Deployment, DevOps & SRE** who also builds software · Ottawa, ON 🇨🇦

5+ years owning the full deployment lifecycle of cloud-hosted platforms.

- 🚀 I build reliable, scalable delivery systems and automate away operational toil
- 🧰 AWS · Docker · Kubernetes · Terraform · GitHub Actions · Grafana · Sumo Logic
- 🎛️ Off the clock, I build full-stack side projects — like Idea2DAW below
- 📫 jeffashong@gmail.com · [LinkedIn](https://linkedin.com/in/mjashong)

---

## 🎹 Featured project — Idea2DAW

**Turn any song reference into a producer-ready starter kit.** Paste a YouTube/Spotify link or upload an audio file, and Idea2DAW extracts **BPM**, **musical key**, **diatonic chords**, **tempo-synced delay times**, **reverb presets**, and **similar reference tracks** — in seconds.

### ▶️ Try it yourself (one command)

You just need [Docker](https://www.docker.com/get-started/):

```bash
docker run --rm -p 3000:3000 ghcr.io/mjashong/idea2daw:latest
```

Then open **http://localhost:3000** — upload an audio file or paste a link and hit analyze. No accounts, no setup.

### 🔬 How it works

- **Key detection** — a Krumhansl-Schmuckler key-finding algorithm over the track's chroma profile, spelled the way producers expect (`Eb`, not `D#`)
- **BPM detection** — a Fourier tempogram refined with inter-onset-interval timing, octave-folded into a musical range
- **Chords / delay / reverb** — derived from the detected key and tempo by a music-theory engine

### 📦 Shipped like production

Packaged as a **single Docker image** with a **CI/CD pipeline** — a GitHub Actions workflow builds on every version tag and publishes to the GitHub Container Registry. Source stays private; the demo is one public command.

**Built with:** Next.js · React · TypeScript · Tailwind · FastAPI · Python · librosa · NumPy/SciPy · ffmpeg · Docker · GitHub Actions

---

## 🧰 Tech I work with

- Cloud & Infra: `AWS` · `Docker` · `Kubernetes` · `Terraform`
- CI/CD & DevOps: `Git` · `GitHub` · `GitHub Actions` · `Jenkins`
- Observability: `Grafana` · `Sumo Logic`
- Languages: `Python` · `Java` · `JavaScript` · `C++` · `SQL` · `Bash`
- Web Dev: `React` · `Node.js` · `Next.js` · `TypeScript`
