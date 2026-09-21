# 🎛️ Cyber-Tactile Control Studio (Flutter)

A sleek, interactive 3D Neomorphic control deck built with Flutter & Dart, demonstrating advanced micro-interactions and state management.

## ✨ Features
- **3D Mechanical Tactile Buttons**: Built using dual opposing `BoxShadow` physics and `GestureDetector` in Fantasy Spellbook theme. There are 4 different tactile buttons named 'CAST', 'WARD', 'HEAL' and 'TELEPORT'. When each button is pressed, the tactile button changes its shadow and icon color, creating 3D feeling.
- **Live State Management**: Real-time tap counts, energy calibration sliders, and status monitors. Every time you press the tactile buttons, the total tap counts increase to show how many times you casted spells. When energy calibration goes above 80%, the background hue changes to alert the user. Once tactile buttons are pressed, a status monitor above the tactile buttons shows what spell has been casted. 
- **Adaptive Theme System**: Seamless switching between Dark Cyber Mode and Light Neomorphic Mode whenever the user clicks the button to change the mode.
- **Modular Component Design**: Reusable `TactileButton` custom widget architecture, which lets the developer to add the new tactile buttons whenever needed.

## 🛠️ Tech Stack
- **Framework**: Flutter (Material 3)
- **Language**: Dart
- **Key Widgets**: `StatefulWidget`, `GestureDetector`, `AnimatedContainer`, `Slider`, `Wrap`
