# Exno.8-Prompt-Engg
### Date: 20-05-2025
### Name: RAMYA R
### Register no: 212223230169
# Aim:
To perform the Exploration of Prompting Techniques for Audio Generation
# Algorithm: 
Explore how various prompting techniques can be used to generate and manipulate audio content (e.g., music, sound effects, voice narration) using AI model

## AI-Tools Requireds

**Eleven Labs**

---

# 🎧 PROMPT

## 🔵 Audio 1:

> “Outside, the relentless rainfall pounds against the windows while distant thunder rumbles like a warning from the depths. Inside the old, forgotten mansion, a fragile piano plays a haunting melody—each note trembling through the air. Suddenly, the heavy door shutter slams shut with a bone-chilling bang, sealing you in darkness. What lurks beyond the shuttered door, waiting to be unleashed?”

## 🎙️ OUTPUT LINK:
https://drive.google.com/file/d/1R057XmNV7HC_bAcMlicFEcYTahvHebSw/view?usp=drive_link


## 🟢 Audio 2:
> Generate an immersive audio scene with continuous light rain and a gentle breeze in the background. Begin with a soft, emotional piano melody playing steadily. As the audio progresses, the piano gradually slows down and fades into the ambiance. Around the midpoint, introduce a series of distant thunder rumbles, slowly increasing in intensity. Include one loud thunderclap in the middle section. Afterward, return to a tranquil atmosphere with only the sound of light rain and breeze, fading out smoothly

## 🎙️ OUTPUT LINK:
https://drive.google.com/file/d/1cJUr2D82d5SpcPJ6vhYCDwcLYFxld5Gw/view?usp=drive_link

---

# PROCEDURE

# 🎧 Creating Ambient + Piano Audio with ElevenLabs

This guide outlines how to use **ElevenLabs** to generate audio that combines soft piano, rain, and thunder — especially for scenes with atmospheric narration or voice.

---

## ✅ Option 1: Using ElevenLabs for Ambient + Piano Scenes

### 🪛 Step-by-Step Procedure

#### 1. Log in / Sign Up
- Visit [https://elevenlabs.io](https://elevenlabs.io)
- Create an account or log in.

#### 2. Navigate to "Speech Synthesis"
- Open the **Speech Synthesis** tool from the dashboard.
- This tool is primarily for generating realistic AI voice audio from text input.

#### 3. Enter a Narration Prompt (Optional for Spoken Scenes)
Example prompt:
> "Imagine a girl playing soft piano by the window as it rains gently outside. Thunder rolls in the distance..."

- Select a calm, emotional voice (e.g., `"Rachel"` or `"Grace"`).
- Set **voice stability** to low and **style** to expressive for natural, ambient delivery.

#### 4. Generate and Download the Audio
- Click **"Generate"** to create the narration.
- Download the file in **MP3** or **WAV** format.

#### 5. Layer Sounds Using Audio Software
Use software like:
- **Audacity**
- **GarageBand**
- **Reaper**

Combine the following elements:
- 🎙️ ElevenLabs narration audio
- 🌧️ Ambient rain and thunder (e.g., from [Freesound.org](https://freesound.org), Envato, or your own files)
- 🎹 Soft piano in the background

**Tip:**  
Ensure that the piano and rain play together throughout, and add louder thunder effects in the middle for dramatic emphasis.

#### 6. Export Final Audio
- Mix all tracks.
- Export the final audio as **MP3** or **WAV**.

---

## 🎧 Alternative Tools (Recommended for Non-Speech Audio)

If narration is **not required**, use these tools for pure ambient or instrumental sound generation:

- [**Suno AI**](https://suno.ai): AI music generation with descriptive prompts.
- **AudioCraft (by Meta)**: Open-source tool for ambient + musical sound creation.
- [**Soundraw.io**](https://soundraw.io): Customizable AI music composition tool.

---

## 📂 Suggested Use Cases
- Ambient soundscapes
- Short films or animations
- Mindfulness/meditation apps
- Narrative podcast intros

---



# 🎧 Audio Comparison Report: Piano + Rain + Thunder

This report provides a technical and creative comparison of two ambient audio samples featuring piano, rain, and thunder elements.

---

## 📂 Files Compared

- `1.mp3` – Soft ambient track (likely piano + rain + horror sound)
- `2.mp3` – Dynamic ambient track (rain + thunder + slower piano)

---

## 🎼 Waveform Analysis

### 🔵 Audio 1 (1.mp3)
- **Mood**: Calm and consistent
- **Amplitude**: Smooth throughout; minimal volume spikes
- **Interpretation**: Likely features steady rain and soft piano with no thunder

### 🟢 Audio 2 (4.mp3)
- **Mood**: Dramatic, dark middle section
- **Amplitude**: Noticeable spikes in the middle (strong thunder)
- **Interpretation**: Features rain, thunder, and a slowing piano progression

![Waveform Comparison](waveform_comparison.png)

---

## 📊 Frequency Spectrum Analysis

### 🔵 Audio 1 (1.mp3)
- **Dominant Frequencies**: Mid and high (500–3000 Hz)
- **Sound Elements**: Piano, light rain
- **Bass Content**: Very low

### 🟢 Audio 2 (4.mp3)
- **Dominant Frequencies**: Full range, strong <500 Hz (bass)
- **Sound Elements**: Thunder (deep bass), rain, piano
- **Spectral Character**: Wide dynamic and tonal range

![Spectrum Comparison](spectrum_comparison.png)

---

## 🧠 Technical Comparison Summary

| Feature              | Audio 1 (`1.mp3`)            | Audio 4 (`4.mp3`)               |
|---------------------|-------------------------------|----------------------------------|
| **Duration Feel**    | Uniform and consistent         | Varies with dynamics             |
| **Amplitude Peaks**  | Low, flat                      | High in middle (thunder)         |
| **Bass Presence**    | Minimal                        | Strong and deep                  |
| **Piano Behavior**   | Steady tempo                   | Slows toward the end             |
| **Atmosphere**       | Gentle rain + piano            | Rain + thunder + slowing piano   |
| **Mood Progression** | Constant calm                  | Calm → dark/dramatic → soft      |

---

## 📝 Suggestions

- Use **Audio 1** for:
  - Background ambiance
  - Meditation or calm focus scenes
  - Horror theme
    
- Use **Audio 2** for scenes that need:
  - A mood shift or dramatic arc (e.g., cinematic or storytelling)
  - Thunder and layered ambient texture
  - Rainy Theme

---

## 🔧 Tools Used for Analysis

- Python (`pydub`, `scipy`, `matplotlib`)
- Waveform + frequency visualizations
- Technical metrics (amplitude, frequency spectrum)

---


# Result:
The Prompt for the above process executed successfully
