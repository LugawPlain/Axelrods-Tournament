# Enigma Machine Simulator

A fully functional, web-based simulator of the famous **Enigma I** machine used by the Wehrmacht during World War II. This project provides an interactive and historically accurate experience of encryption and decryption using the Enigma mechanism.

## 🌟 Features

*   **Accurate Simulation**: Replicates the internal wiring and mechanics of the Enigma I (Reflector B).
*   **Rotor System**:
    *   Select from Rotors I, II, and III.
    *   Adjust Ring Settings (Ringstellung).
    *   Set Initial Rotor Positions (Grundstellung).
    *   Authentic stepping mechanism (including the "double step" anomaly).
*   **Plugboard (Steckerbrett)**:
    *   Connect letter pairs to swap signals before they enter the rotors.
    *   Real-time validation for duplicates and self-connections.
*   **Interactive Interface**:
    *   **Lampboard**: Visual feedback with glowing lamps for encrypted output.
    *   **Keyboard**: Clickable keys and physical keyboard support.
    *   **Textures**: Wood and metal textures for a retro feel.
*   **Message History**:
    *   Automatically logs encrypted messages.
    *   Saves the *exact* machine state (Rotor positions, Ring settings, Plugboard) for each message.
    *   **One-Click Restore**: Click any saved message to instantly restore the machine to that state and decrypt the message.

## 🚀 How to Use

1.  **Open the Simulator**: Simply open `index.html` in any modern web browser. No installation required.
2.  **Configure the Machine**:
    *   **Rotors**: Choose your rotors (Left, Middle, Right) and set their Ring settings (1-26) and starting positions (A-Z).
    *   **Plugboard**: Enter pairs of letters to swap (e.g., `AB CD XY`).
3.  **Encrypt/Decrypt**:
    *   Type your message using your physical keyboard or the on-screen keys.
    *   The **Lampboard** will light up to show the encrypted character.
    *   The encrypted text will appear in the output display.
4.  **Save & Restore**:
    *   Press `Enter` or click "SAVE & CLEAR" to save your message to the history log.
    *   Click on any message in the **Message Log** to restore the machine settings used for that message. This allows you to easily decrypt saved messages.

## 🛠️ Technical Details

*   **Tech Stack**: HTML5, CSS3 (Tailwind CSS via CDN), Vanilla JavaScript.
*   **Single File**: The entire application is contained within `index.html` for easy portability.
*   **Design**: Responsive design with a dark, tactical aesthetic using `Courier Prime` and `Special Elite` fonts.

## 📜 License

This project is open-source and available for educational and personal use.