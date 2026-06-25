# SEC411 AI Security Labs - Student Distribution

Official distribution repository for SANS SEC411 AI Security Essentials course labs.

## 🚀 Quick Start

1. **Download the latest release**: [Releases page](https://github.com/sethmisenar/411_labs_releases/releases/latest)
2. **File to download**: `sec411-labs-vX.X.X.zip` (password-protected)
3. **Password**: Provided in your SANS course materials
4. **Extract locally and run setup**: Follow the included `QUICKSTART.md`

The ZIP is intentionally small. Setup downloads the larger container images and model assets the first time you run the labs.

## 📦 What's Included

- **Hands-on labs** covering AI security fundamentals
- **Web-based interface** - no coding required
- **Docker containers** - cross-platform compatibility
- **Progressive hints** - learn at your own pace

## 📋 System Requirements

- Docker Desktop installed and running
- 16 GB system RAM recommended
- Docker memory: 4 GB minimum, 6-8 GB recommended
- 20 GB free disk space recommended
- Modern web browser (Chrome, Firefox, Edge, Safari)
- Ports 8800-8804 and 3800-3804 available

## 🔐 About This Repository

This repository contains **only student distribution packages**. Source code is maintained in a private repository.

Each release includes:
- Password-protected ZIP with lab materials
- SHA256 checksum for verification
- Release manifest with container image references

## 🆘 Support

- Check included `QUICKSTART.md` for setup instructions
- Ask in **#sec411-labs** on the SEC411 Slack workspace
- Use `/support` in Slack for direct support

If setup fails with certificate, TLS, or model-download errors on a restricted corporate network, mention "restricted network" or "offline bundle" when asking for help. The normal release ZIP does not include offline model bundles; support can help determine whether you need a corporate CA fix or an offline bundle path.

## 📚 Course Information

**Course**: SANS SEC411 - AI Security Essentials
**Labs**: Tokenization Security, Prompt Injection, RAG Security
**License**: Educational use only - SANS Training

---

**Note**: Container images are hosted on GitHub Container Registry (ghcr.io) and are automatically pulled during setup.
