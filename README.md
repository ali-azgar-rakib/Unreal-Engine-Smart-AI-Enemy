# Advanced Enemy AI System – Unreal Engine

## 📌 Project Status

🚧 **Work in Progress** 
---

## 🤖 AI Behavior Features

- 🧠 **Dynamic Cover Seeking**  
  - Enemy uses **Environment Query System (EQS)** to locate nearby walls or obstacles.  
  - Seeks cover strategically based on line-of-sight to the player.

- 🕐 **Delayed Ambush Attack**  
  - Once hidden, enemy waits for a short delay (e.g., 1 second).  
  - Then leaves cover to initiate an attack on the player.

- ⚡ **Teleportation Defense**  
  - If the player gets too close to the enemy, it will **teleport** to a random safe location.  
  - Prevents melee attacks or close-range exploitation.

- ❤️ **Emergency Health Boost**  
  - When the enemy’s health drops to a critically low level, it triggers a self-heal ability.  
  - Temporary invincibility or buff may be applied during boost period.

---

## 🛠️ Technologies & Systems Used

- 🎮 **Unreal Engine Behavior Tree**  
  - Modular decision-making logic for AI sequences and fallback strategies.

- 🌐 **Unreal Engine EQS (Environment Query System)**  
  - Enables dynamic querying of the environment for hiding spots and teleport destinations.

- 👁️‍🗨️ **AI Perception System**  
  - **Sight (Vision)**: Detects player presence in line-of-sight.  
  - **Hearing (Sound)**: Reacts to footsteps, gunshots, and other noise events.


---
