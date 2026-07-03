# RTX 5090 + Adobe Premiere Pro & After Effects Performance Investigation

> A real-world technical investigation into Adobe Premiere Pro and After Effects performance issues on NVIDIA RTX 5090.

---

# Project Overview

This repository documents a real-world investigation of Adobe Premiere Pro and After Effects performance on a high-end workstation.

The objective is to identify the root cause of poor performance using systematic testing rather than assumptions.

Every test is documented with screenshots, hardware specifications, software versions, BIOS settings, driver versions and benchmark results.

This repository will continue to be updated as new tests are completed.

---

# Current Hardware

| Component | Specification |
|------------|---------------|
| CPU | Intel Core Ultra 9 285K |
| GPU | Gigabyte AORUS GeForce RTX 5090 32GB |
| RAM | 128GB DDR5 6000MHz |
| Motherboard | ASUS ROG Maximus Z890 HERO |
| System SSD | Samsung 990 PRO 2TB |
| Project SSD | WD_BLACK SN8100 PCIe 5.0 2TB |
| OS | Windows 11 Pro |

---

# Adobe Applications Tested

- Adobe Premiere Pro
- Adobe After Effects
- Adobe Media Encoder
- Dynamic Link
- Motion Graphics Templates (MOGRT)
- Envato Templates

---

# Main Problems

- Very slow Premiere Pro startup
- Very slow After Effects startup
- Heavy MOGRT templates freeze
- Envato templates become unresponsive
- White screen while loading
- Dynamic Link is slow
- GPU usage unexpectedly low
- CPU usage unexpectedly low
- Adobe 2026 performs significantly worse than previous versions

---

# Investigation Rules

Every modification is tested individually.

No assumptions.

No sponsored content.

Only reproducible results.

Every result is documented before moving to the next test.

---

# Current Status

## Adobe Premiere Pro 2026

Result:

❌ Poor performance

Symptoms:

- Startup is slow
- Heavy MOGRT templates freeze
- White screen appears
- Poor responsiveness

---

## Adobe Premiere Pro 25.6.1

Result:

✅ Noticeably improved

Observed improvements:

- Faster startup
- Heavy MOGRT templates begin loading instead of freezing
- White screen issue significantly reduced
- GPU utilization improved
- Overall responsiveness improved

Performance is still not fully optimized and further investigation is ongoing.

---

# Investigation Progress

- [x] BIOS updated
- [x] Intel ME updated
- [x] NVIDIA Studio Driver installed
- [x] Chipset drivers updated
- [x] Storage health verified
- [x] GPU verified
- [x] Adobe 2026 tested
- [x] Adobe 25.6.1 tested
- [ ] Adobe 24.x testing
- [ ] PugetBench benchmark
- [ ] NVIDIA Nsight analysis
- [ ] Adobe log analysis

---

# Goal

Identify the exact reason why Adobe Premiere Pro and After Effects perform below expectations on an RTX 5090 workstation and provide verified solutions for other professionals experiencing similar issues.
