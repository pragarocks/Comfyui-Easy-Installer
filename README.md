<div align="center">

# ComfyUI Easy Install — Lokesh RV Edition

**Windows-க்கான ஒரே கிளிக் ComfyUI நிறுவியர் | One-click ComfyUI Installer for Windows**

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![NVIDIA](https://img.shields.io/badge/NVIDIA-GPU-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.12.10-3776AB?style=for-the-badge&logo=python&logoColor=white)

</div>

---

## வணக்கம்! 🙏

என் பெயர் **Lokesh RV**. இந்த திட்டம் எனது நண்பர்களுக்காக உருவாக்கப்பட்டது — ComfyUI-ஐ எளிதாக நிறுவி, என்னுடைய workflow-களை நேரடியாக பயன்படுத்திக்கொள்ளலாம்.

> *"தொழில்நுட்பம் அனைவருக்கும் எளிதாக இருக்க வேண்டும்."*

---

## என்ன கிடைக்கும்? / What's Included?

- **ComfyUI** — சக்திவாய்ந்த AI Image & Video Generation கருவி
- **Python 3.12.10** — Embedded (தனியாக நிறுவ வேண்டியதில்லை)
- **20+ Custom Nodes** — Image, Video, Audio & Utility nodes
- **Lokesh RV Workflows** — என்னுடைய தயாரான workflow-கள் நேரடியாக ComfyUI-இல் கிடைக்கும்

---

## நிறுவுவது எப்படி? / How to Install

1. இந்த repo-வை **Download as ZIP** செய்யுங்கள் அல்லது clone செய்யுங்கள்
2. ZIP-ஐ ஒரு புதிய folder-இல் extract செய்யுங்கள்
3. `ComfyUI-Easy-Install-LokeshRV.bat` கோப்பை இயக்குங்கள்
4. நிறுவல் தானாகவே நடக்கும் — காத்திருங்கள்!
5. முடிந்தவுடன் `ComfyUI-Easy-Install/Add-Ons/Tools/Start ComfyUI.bat` மூலம் தொடங்குங்கள்

> **முக்கியம்:** Administrator ஆக இயக்க வேண்டாம். `C:\`, `Program Files` போன்ற system folder-களை தவிர்க்கவும்.

---

## Lokesh RV Workflows

`LokeshRV-Workflows/` folder-இல் உள்ள என்னுடைய workflow JSON கோப்புகள் நிறுவலின்போது தானாகவே இங்கே நகலெடுக்கப்படும்:

```
ComfyUI/user/default/workflows/Lokesh RV/
```

ComfyUI-ஐ திறந்தவுடன் மேல் மூலையில் உள்ள **Workflows** பட்டியலில் காணலாம்.

---

## தேவைப்படுவது / Requirements

| தேவை | விவரம் |
|---|---|
| OS | Windows 10 / 11 (64-bit) |
| GPU | NVIDIA (Driver 580+) |
| RAM | 16 GB+ பரிந்துரைக்கப்படுகிறது |
| Storage | 20 GB+ காலியாக இருக்க வேண்டும் |
| Internet | நிறுவலின்போது தேவை |

---

## Included Nodes

<details>
<summary>அனைத்து nodes-ஐயும் காண விரிக்கவும்</summary>

| வகை | Node |
|---|---|
| Manager | ComfyUI Manager |
| Utility | Easy-Use, KJNodes, rgthree, iTools, ControlAltAI |
| Image | TiledDiffusion, Inpaint CropAndStitch, ControlNet Aux, LayerStyle, RMBG, Easy-Sam3, SCAIL-Pose |
| Video | VideoHelperSuite, WanVideoWrapper, WanAnimatePreprocess, SeedVR2 VideoUpscaler |
| Audio | MelBandRoFormer, Qwen3-TTS, FishAudio S2 |
| Models | GGUF, QwenVL, ComfyUI-Pixaroma |

</details>

---

## Auto-Sync (GitHub Actions)

இந்த repo-வில் ஒரு **daily cron job** உள்ளது (`.github/workflows/sync-upstream.yml`).
Pixaroma-வின் original installer புதுப்பிக்கப்படும்போது, தானாகவே இந்த LokeshRV version-உம் புதுப்பிக்கப்படும்.

---

## Credits

- Original installer by [**ivo / Tavris1**](https://github.com/Tavris1/ComfyUI-Easy-Install) — Pixaroma Community
- Customised & maintained by **Lokesh RV**

---

<div align="center">

உங்கள் படைப்பாற்றலுக்கு வாழ்த்துகள்! 🎨

*Happy Creating — Lokesh RV*

</div>
