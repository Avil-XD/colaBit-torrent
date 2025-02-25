<div align="center">

```
   ______      __      ____  _ __ 
  / ____/___  / /___ _/ __ )(_) /_
 / /   / __ \/ / __ `/ __  / / __/
/ /___/ /_/ / / /_/ / /_/ / / /_  
\____/\____/_/\__,_/_____/_/\__/  
```

# C0LAB1T

Your Browser-Based Torrent Command Center

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Avil-XD/colaBit-torrent/blob/master/colaBit.ipynb)
[![GitHub license](https://img.shields.io/github/license/Avil-XD/colaBit-torrent)](https://github.com/Avil-XD/colaBit-torrent/blob/master/LICENSE)
[![GitHub stars](https://img.shields.io/github/stars/Avil-XD/colaBit-torrent)](https://github.com/Avil-XD/colaBit-torrent/stargazers)

</div>

---

> Transform your browser into a powerful torrent downloader using Google's infrastructure. Download at high speeds with up to 350GB of cloud storage - no installation needed!

## ⚡ Key Features

```
┌─────────────────────────────────┐
│ POWER CAPABILITIES             │
├─────────────────────────────────┤
│ ✦ Google Server-Speed Downloads│
│ ✦ Up to 350GB Cloud Storage   │
│ ✦ Pure Browser Operation      │
│ ✦ Parallel Download Support   │
│ ✦ Auto File Compression      │
└─────────────────────────────────┘
```

## 🚀 Technical Stack

```python
# Core Dependencies
LIBRARIES = {
    'libtorrent': 'Primary torrent handler',
    'wget': 'Torrent file downloader',
    'torf': 'Torrent processing',
    'zipfile': 'Auto compression'
}

# Download Configuration
STORAGE_PATH = '/content/Torrent/'
OUTPUT_FILE = 'Downloaded-Torrent.zip'
PORTS = range(6881, 6891)
```

## 📦 Installation

The notebook automatically installs all required dependencies:

```bash
# System Dependencies
$ apt install python3-libtorrent

# Python Packages
$ pip install --upgrade pip setuptools wheel
$ pip install lbry-libtorrent wget torf
```

## 🚀 Usage Guide

### 1. Launch
```
➜ Click "Open in Colab" above
➜ Runtime starts automatically
```

### 2. Input
```
Supports:
✓ Magnet links
✓ .torrent file URLs (auto-converts to magnet)
```

### 3. Download Process
```python
# Actual download states:
STATES = [
    'queued',
    'checking',
    'downloading metadata',
    'downloading',
    'finished',
    'seeding',
    'allocating'
]

# Progress info shown:
- Download percentage
- Speed (up/down KB/s)
- Peer count
- Current state
```

## 💾 Storage Options

```python
# Available Modes:
BASIC = "80GB"    # Default mode
PRO = "350GB"     # With GPU runtime

# Enable PRO mode:
1. Runtime > Change runtime type
2. Hardware accelerator > GPU
3. Save
```

## ⚡ Advanced Features

```
[SYSTEM CAPABILITIES]
├── 🔄 Parallel downloading
├── 🎯 DHT network enabled
├── 🔄 Auto magnet conversion
├── 📊 Real-time progress tracking
└── 🗜️ Automatic ZIP compression
```

## ⚠️ Troubleshooting

```
[COMMON SOLUTIONS]
┌────────────────┬────────────────────┐
│ Issue          │ Fix               │
├────────────────┼────────────────────┤
│ Slow Speed     │ Check peer count  │
│ Space Full     │ Enable GPU mode   │
│ Metadata Stuck │ Allow completion  │
│ ZIP Error      │ Check free space  │
└────────────────┴────────────────────┘
```

## 🛡️ Usage Guidelines

```
[SAFETY RULES]
├── 📋 Follow copyright laws
├── ✅ Respect Colab terms
└── 🛡️ Use responsibly
```

## 🤝 Community

```
[JOIN US]
├── 🐛 Report issues
├── 💡 Request features
└── 🔧 Submit PRs
```

---

<div align="center">

### Quick Links
[![Report Bug](https://img.shields.io/badge/Report-Bug-red)](https://github.com/Avil-XD/colaBit-torrent/issues)
[![Request Feature](https://img.shields.io/badge/Request-Feature-green)](https://github.com/Avil-XD/colaBit-torrent/issues)
[![Join Chat](https://img.shields.io/badge/Join-Discussion-blue)](https://github.com/Avil-XD/colaBit-torrent/discussions)

</div>
