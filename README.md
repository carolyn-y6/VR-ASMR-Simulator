# VR ASMR Simulator 🎧🌌

An immersive virtual reality experience designed to trigger Autonomous Sensory Meridian Response (ASMR) through customizable, user-driven sensory environments.

---

## 📖 What is ASMR?

**Autonomous Sensory Meridian Response (ASMR)** is a calming, tingling sensation that typically begins on the scalp and moves down the neck and spine. It's often triggered by specific auditory or visual stimuli such as:

- Whispering or soft speaking
- Tapping, brushing, or crinkling sounds
- Personal attention role-plays
- Slow, deliberate hand movements

Because ASMR triggers are **highly personal**—what works for one person may do nothing for another—our simulator puts you in control.

---

## 🧠 Why We Built This

Traditional ASMR videos are passive. You watch, you listen, but you can't interact or adapt the experience to your unique trigger profile.

**VR ASMR Simulator** was created to:

- **Enhance immersion** using VR's spatial presence and 360° environments
- **Empower personalization**—choose, combine, and adjust triggers in real time
- **Maximize tingles**—let you fine-tune visual, auditory, and haptic feedback to your specific sensitivities
- **Lower the barrier to entry**—support for both high-end VR and smartphone-based headsets

> 🎯 *Our goal: Move from one-size-fits-all ASMR to a deeply personal relaxation tool, accessible to more people.*

---

## 🚀 Key Features

- **Customizable Trigger Library** – Mix sounds, objects, and interactions
- **Dual Input Modes**:
  - **Leap Motion** – Natural hand tracking (high immersion)
  - **Google Cardboard** – Gaze-based interaction (accessible, no extra hardware)
- **Spatialized Audio** – Steam Audio for 3D sound positioning
- **Multiple Environments** – Calm rooms, nature settings, abstract sensory spaces
- **Real-time Adjustment** – Change trigger intensity, speed, and proximity

---

## 🛠️ Tech Stack

| Technology | Purpose |
|------------|---------|
| **Unity** | Game engine & VR integration |
| **C#** | Core logic & interaction scripting |
| **Leap Motion** | High-end hand tracking |
| **Google Cardboard SDK** | Mobile VR & gaze input |
| **Steam Audio** | Spatialized 3D sound |
| **Blender** | 3D asset & environment modeling |

---

## 📱 Supported Platforms

| Platform | Input Method | Best For |
|----------|--------------|----------|
| **Any smartphone + Google Cardboard** | Gaze + single button | Accessibility, portability, low cost |
| **Desktop (no VR)** | Mouse + keyboard (debug mode) | Development & testing |

---

## 🧩 Challenges & Solutions

| Issue | Description | Mitigation |
|-------|-------------|-------------|
| **Unity as a "Black Box"** | First-time Unity users; felt overwhelmed by editor, rendering pipelines, XR interaction toolkit. | Spent 2 weeks on structured tutorials; created a minimal "white box" prototype before adding visuals. |
| **Leap Motion Calibration** | Hands would drift, jitter, or appear at wrong depth/rotation; broke immersion. | Adjusted physical mounting angle; wrote custom offset correction script; limited interaction zone to calibrated range. |
| **Performance** | High poly Blender assets + real-time audio caused frame drops on mobile. | Optimized meshes (decimation in Blender); separate low-poly assets for Cardboard builds. |

---

## 🧪 Getting Started

### For Google Cardboard (Mobile)

#### Prerequisites
- **Any Android smartphone** (Android 8+ / iOS 12+)
- **Leap Motion Controller** (mounted on headset)
- **Google Cardboard** (any version) or compatible viewer
- **Google Cardboard SDK for Unity** (v1.6+)
- **Unity** with Android/iOS build support
