Cheese N’ Chaos 🎮
🎯 Overview
Game ini dirancang sebagai latihan Unity yang berfokus pada:
Scene flow & level management
AI movement dasar
Timer real-time
Win/Lose logic
SFX integration
Simple simulation mechanics

🧩 Gameplay
1. Cheese Mode 🧀
Player dapat spawn cheese untuk memberi makan tikus.
Tikus bergerak otomatis menuju cheese terdekat.
Jika dua tikus dewasa makan cheese secara bersamaan → terjadi perkembangbiakan, dan akan muncul baby rat.

2. Gun Mode 🔫
Dari proses perkawinan tikus, menghasilkan peluang 25% muncul tikus kanibal.
Tikus kanibal menyerang dan memakan tikus lain.
Player harus menembak tikus kanibal untuk menjaga populasi tetap aman.

📊 Level Objective
Setiap level memiliki target populasi (contoh: 15/20/30 rats).
Untuk menang, player harus:
Mencapai populasi tikus sesuai target
Mengendalikan kanibal agar populasi tidak musnah
Memanfaatkan cheese spawn dan kontrol situasi
Jika waktu habis dengan populasi tidak mencapai target → level fail.

✨ Features
⏱️ Timer System
🎯 Level Manager (target-based progression)
👇 Two Game Modes (Cheese Mode & Gun Mode)
🐀 AI Rat Breeding & Movement 
🧮 Dynamic Population Scoring
💥 Cannibal Rat Spawn System
🔊 SFX (shoot, winlose, UI)
🖥️ Win / Lose Screen
🔁 Retry / Next Level System

🛠️ Tech Stack
Engine: Unity
Language: C#
Tools: Unity Input System, prefabs, scene manager
Version Control: Git + GitHub

👤 Author
Project dikembangkan melalui kolaborasi tim dengan kontribusi sebagai berikut:
Eveline Marvelia - Game System dan UI 
Bertanggung jawab atas system permainan seperti 
timer, score, levelling, sound dan interface in game user.

Frederick Garner Wibowo - Gameplay dan Mechanic  
Bertanggung jawab atas mekanisme gameplay 
utama seperti breeding, spawning, eating, killing, 
animation and title screen 

Shakira Salvia Nesya - Tutorial dan Win/Lose Screen 
Bertanggung jawab atas mengatur teks dan pesan 
yang muncul saat pemain menang atau kalah 
(Win/Lose) yang dimuat dalam scene Tutorial. 
