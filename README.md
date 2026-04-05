<div align="center">
  <img src="https://raw.githubusercontent.com/capture0x/capture0x/main/retro-animation-final.gif" width="900" height="500">
  <h1>tmrswrr</h1>
  <p><strong>Security Researcher</strong> • Tool Developer • Offensive Security</p>
</div>

---

## 🔭 Featured Projects

| Project | Description |
|---------|-------------|
| [AWS Pentest Tool](https://github.com/capture0x/aws-pentest) | AWS audit & offensive assessment toolkit |
| [AI Cyber Agent](https://github.com/capture0x/ai-cyber-agent) | AI-assisted security workflow automation |
| [My-Exploits](https://github.com/capture0x/My-Exploits) | Exploit collection & practical research |
| [Bug-Hunter](https://github.com/capture0x/Bug-Hunter) | Bug hunting & recon tooling |

## 🛠️ Security Tools

- [Web-Scanner](https://github.com/capture0x/web-scanner/)
- [XSS-LOADER](https://github.com/capture0x/XSS-LOADER)
- [Lfi-Space](https://github.com/capture0x/Lfi-Space)
- [Dork-Scan](https://github.com/capture0x/Dork-Scan/)
- [SSTI-Finder](https://github.com/capture0x/SSTI-FINDER)
- [Lfi-Finder](https://github.com/capture0x/LFI-FINDER)
- [XSS-FINDER](https://github.com/capture0x/XSS-FINDER)

## 🔬 Research

- [My-CVE](https://github.com/capture0x/My-CVE)
- [CVE-FIND](https://github.com/capture0x/CVE-FIND)
- [Cypher](https://github.com/capture0x/cypher)
- [EvilEyes-Extract](https://github.com/capture0x/EvilEyes-Extract)
- [XSHOCK](https://github.com/capture0x/XSHOCK)
- [XCTR-Hacking-Tools](https://github.com/capture0x/XCTR-Hacking-Tools)

## 📊 Stats

<p align="center">
  <img src="https://i.imgur.com/cpz9SUO.gif" alt=":tmrswrr" width="900">
</p>

name: Generate Snake
on:
  schedule:
    - cron: "0 */6 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: capture0x
          gif_out_path: dist/github-snake.gif
          svg_out_path: dist/github-snake.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
---

## 🎥 Latest YouTube Videos

<!-- YOUTUBE:START -->
- [Xss Payload Generator](https://youtu.be/ys_a5yx1hmY)
- [SSTI Finder Tool](https://youtu.be/RftxyB9tlI4)
- [LFI Space Tool](https://youtu.be/rpcGqwZU2As)
- [LFI Finder Tool](https://youtu.be/g01MZMGm3Cc)
- [CYPHER TOOLS](https://youtu.be/M4eq6JUMffI)
- [Exploit Finder](https://youtu.be/J6HXwa6NVe8)
- [WATCH COINS](https://youtu.be/EV_fCFO79cY)
- [xShock ShellShock](https://youtu.be/VXP6ZYyBPS4)
- [XCTR Hacking Tool](https://youtu.be/nRpO9w_V1ZA)
<!-- YOUTUBE:END -->

---

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=capture0x&label=Profile%20views&color=0e75b6&style=flat" alt="Profile Views" />
</div>
