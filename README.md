<div align="center">
  <img alt="Swiss Made Software" src="https://img.shields.io/badge/Swiss_Made_Software-white?logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAzMiAzMiI%2BPHJlY3Qgd2lkdGg9IjMyIiBoZWlnaHQ9IjMyIiBmaWxsPSIjRDUyQjFFIi8%2BPHJlY3QgeD0iMTMiIHk9IjYiIHdpZHRoPSI2IiBoZWlnaHQ9IjIwIiBmaWxsPSIjRkZGIi8%2BPHJlY3QgeD0iNiIgeT0iMTMiIHdpZHRoPSIyMCIgaGVpZ2h0PSI2IiBmaWxsPSIjRkZGIi8%2BPC9zdmc%2B">
  <img alt="nDSG & GDPR Compliant" src="https://img.shields.io/badge/Privacy-nDSG_%26_GDPR_Compliant-brightgreen">
</div>
<br>
<br>
<div align="center">
  <img src="https://www.pid-piper.shumil.in/icon.png" alt="PID Piper Logo" width="128" height="128" />
</div>

# PID Piper

**The modern Blackbox log analyzer for FPV pilots.**

PID Piper helps you tune your drone with confidence. Drop in a `.bbl` or
`.bfl` log from Betaflight or INAV and get instant, interactive insights:
step response, filter performance, throttle spectrograms, and more — all
running locally on your machine.

<p align="center">
  <img alt="Platforms" src="https://img.shields.io/badge/platforms-macOS%20%7C%20Windows%20%7C%20Linux-blue">
  <a href="https://github.com/ishumilin/pid-piper/blob/master/LICENSE.md">
    <img alt="License" src="https://img.shields.io/badge/license-Freeware%20(Non--Commercial)-green">
  </a>
  <a href="https://pid-piper.shumil.in">
    <img alt="Website" src="https://img.shields.io/badge/website-pid--piper.shumil.in-blue">
  </a>
  <br>

</p>

![PID Piper Screenshot](https://www.pid-piper.shumil.in/screenshot.png)

## ⬇️ Download

Pick the right build for your machine on the
[Releases page](https://github.com/ishumilin/pid-piper/releases/latest):

| OS      | File |
| --------| ---- |
| macOS   | `PID-Piper-x.x.x-mac-x64.dmg` (Intel) / `-arm64.dmg` (Apple Silicon) |
| Windows | `PID-Piper-x.x.x-win-x64-setup.exe` (Installer) / `-portable.exe` / `.msi` |
| Linux   | `PID-Piper-x.x.x-linux-x64.AppImage` / `.deb` / `.rpm` |

> **Heads-up:** the app is currently unsigned. On Windows, click "More info" → "Run anyway" if SmartScreen warns you. 
> On macOS Intel (`x64`), right-click → Open the first time. 
> On macOS Apple Silicon (`arm64`), the quarantine flag will cause the app to bounce forever. Run this in Terminal to fix it:
> `xattr -cr "/Applications/PID Piper.app"`

## ✨ Features

### Time Trace
Overlay gyro / setpoint / motor traces with optional PID terms.
![Time Trace](https://www.pid-piper.shumil.in/time-trace.png)

### Step Response
Measure exactly how your drone reacts to stick input.
![Step Response](https://www.pid-piper.shumil.in/step-response.png)

### Filter Performance (PSD)
Visualize noise across frequencies.
![Filter Performance](https://www.pid-piper.shumil.in/spectral.png)

### Spectrograms (Time & Throttle)
Track resonance over time and per throttle %.
![Spectrogram](https://www.pid-piper.shumil.in/spectrogram.png)
![Throttle Spectrogram](https://www.pid-piper.shumil.in/throttle-spectrogram.png)

### PID Error
See how well the controller tracks setpoints in scatter plots.
![PID Error](https://www.pid-piper.shumil.in/pid-error.png)

### Flight Statistics
G-force, vibration, battery, GPS at a glance.

## 🔄 Auto-updates

PID Piper checks for updates in the background and installs them on next quit.
You can opt into the **Beta channel** in `Settings → Updates` to receive
pre-releases earlier.

## 🔒 Privacy

Your log files **never leave your computer**. The app uses anonymous error and
usage telemetry to help us fix bugs faster — see the
[Privacy Policy](https://github.com/ishumilin/pid-piper/blob/master/PRIVACY.md)
for full details. You can disable telemetry by blocking outbound traffic to
the configured endpoints.

## 📜 License

PID Piper is **freeware for personal, non-commercial use**. Commercial use
(including paid drone-tuning services) requires a separate license — see
[`LICENSE.md`](https://github.com/ishumilin/pid-piper/blob/master/LICENSE.md).

## 🐛 Bug reports & feedback

Please file issues on **this repository** (`ishumilin/pid-piper`) — the source
code lives in a separate private repository.

## ❤ Sponsor

If PID Piper is useful to you and you want to keep it free for everyone,
please consider [sponsoring on GitHub](https://github.com/sponsors/ishumilin) or

<div align="center">
  <a href="https://www.buymeacoffee.com/ishumilin">
    <img alt="Buy Me A Coffee" src="https://img.shields.io/badge/Buy%20Me%20A%20Coffee-FFDD00?logo=buy-me-a-coffee&logoColor=black">
  </a>
</div>