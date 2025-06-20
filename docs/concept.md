# SIGAR 1.0 – Product Concept (docs/)

## ✨ Project Overview

SIGAR is a portable, app-controlled WiFi signal analysis device focused on 5GHz scanning, authentication triggers, and minimalist design. It is the first version of a planned product line positioned as a high-performance alternative to Flipper Zero.

Target audience: IT security professionals, makers, penetration testers, network analysts.

---

## 🔹 Features (Version 1.0)

* 5GHz WiFi scan using Spacehuhn-style deauthentication function
* Smartphone-controlled interface (WiFi/Bluetooth)
* Start/stop via app or physical button
* LED status indicator
* USB-C port (charging & communication)
* Rechargeable battery-powered

**No display** in version 1.0 – fully operated via mobile UI.

---

## 📅 Development Roadmap

| Phase        | Goal                                 | Status      |
| ------------ | ------------------------------------ | ----------- |
| Prototype    | Hardware complete, firmware in dev   | ✅ Ongoing   |
| App UI       | Basic controls: Start/Stop/Status    | ⏳ Planned   |
| Beta Testing | Internal tests with limited devices  | ⏳ Next Step |
| Crowdfunding | Kickstarter/Indiegogo preview launch | ⏳ In prep   |

---

## 📈 Unique Selling Points / Differentiators

* More compact than Flipper Zero
* Faster access to key functions (Deauth/Scan)
* Clear UX via app instead of mini display
* Less "toy-like", more focused on practical use

---

## 🎨 Mockups (UI Ideas)

### Smartphone App Mockup (Text-based)

**Home Screen:**

* SIGAR Status: "Connected"
* Button: \[Start Deauth]
* Button: \[Stop Deauth]
* Display: "Clients in Range: 12"
* Display: "Target Network: \[SSID]"
* \[Select Target Network] (Dropdown)

**Future Tabs:**

* Scan Overview (networks + RSSI)
* Device Status (Battery, Uptime)
* Logs (Session reports)

---

## 🏠 Housing & Hardware Design (Summary)

* Core: ESP32-C5 DevKit1
* Compact, clean outer shell (CAD ready)
* USB-C, status LED, optional button
* No visible input elements beyond power toggle

---

## 🔐 Security & Legal Notes

* For use only in authorized or owned networks
* Unauthorized interference prohibited
* Clear warnings in UI and on packaging planned

---

## ⚡ Next Steps

* Create and test UI graphics
* Develop app MVP
* Prepare crowdfunding page (text & video)
* Launch GitHub discussions for community feedback
