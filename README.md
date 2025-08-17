# 🤖 Language-Instructed Robotic Arm (LLM + Simulation Demo)

This project demonstrates a simulated robotic arm that can understand and respond to natural language instructions. The system takes a voice command (e.g., "move the red block on the yellow cube"), interprets spatial intent, and controls a robotic arm to execute the task in real time.

Built using a combination of **speech-to-text**, **prompt-engineered instruction data**, and a **fine-tuned GPT-3.5 Turbo model**, this project explores how large language models can be grounded in simulated physical environments.

---

## 📹 Demo Videos

| Voice Command | Video |
|---------------|-------|
| "Pick up the red cube next to the black one" | [![Demo 2](https://img.youtube.com/vi/5sRKFwPjiTE/0.jpg)](https://youtube.com/shorts/5sRKFwPjiTE) |
| "Stack the brown cube next to the yellow cube" | [![Demo 3](https://img.youtube.com/vi/Fj-wdPBOoEY/0.jpg)](https://youtube.com/shorts/Fj-wdPBOoEY) |
| "Place the blue cube on the red one and the yellow cube on the blue cube" | [![Demo 1](https://img.youtube.com/vi/5JA7fOdkMO8/0.jpg)](https://youtube.com/shorts/5JA7fOdkMO8) |

---

## 🧠 System Overview

- **Speech-to-Text**: Converted spoken queries into text using Whisper.
- **Instruction Dataset**: Built a custom dataset of `{User Query, Object Positions, Robot Instruction}` triplets via prompt engineering with Claude 3.7 and GPT-4o.
- **Fine-Tuning**: Fine-tuned GPT-3.5 Turbo on the dataset to generate robot-friendly control instructions.
- **Simulation**: Deployed in a Unity-based simulated environment for real-time task execution.

---

## 📁 Dataset

The fine-tuning dataset used for this project is available in the [`/data`](./data) directory (to be uploaded). It contains structured examples used for instruction tuning, focusing on spatial reasoning and object manipulation tasks.

---

## 🚧 Code Availability

The code for this project is available in [this repository](https://github.com/AnishParkhe/llm-robosim-code)

---
