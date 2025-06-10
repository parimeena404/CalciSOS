# CalciSOS – A Hidden SOS Trigger Inside a Calculator

**CalciSOS** is a discreet, browser-based calculator with an integrated emergency alert feature. On the surface, it behaves like a regular calculator. But when a specific input (`911=`) is entered, it activates a hidden SOS function: prompting for an email address and sending an alert message along with the user's location.

This project is entirely self-contained in a single HTML file, combining structure, style, and logic in one place — ideal for quick deployment and easy integration into awareness tools or personal safety kits.

---

## How It Works

- The interface looks and behaves like a basic calculator.
- When the user types `911=` and presses equals, an input prompt appears asking for an email.
- Upon confirmation, the system:
  - Collects the device’s approximate location
  - Sends an alert message with the location to the entered email address

This happens without disrupting the user experience, making it a subtle but powerful safety mechanism.

---

## Project Highlights

- **Fully functional calculator UI**
- **Hidden trigger pattern (`911=`)**
- **Geolocation-based SOS alert system**
- **Email prompt and alert sender**
- **Single HTML file** — includes embedded CSS and JavaScript
- No external frameworks or dependencies

---

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/parimeena404/CalciSOS.git
