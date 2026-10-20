# 🌿 KuifiMapu — Base Builder Grant Application Proposal (2026)

**Project Name:** KuifiMapu — Open-Source Regenerative Environmental IoT & Ancestral Wisdom on Base  
**GitHub Repository:** [https://github.com/KuifiMapu/KuifiMapu](https://github.com/KuifiMapu/KuifiMapu)  
**Live Giveth Campaign:** [https://giveth.io/project/kuifimapu:-ancestral-wisdom-low-cost-iot-a-home-for](https://giveth.io/project/kuifimapu:-ancestral-wisdom-low-cost-iot-a-home-for)  
**Builder Wallet (Base L2):** `0x2821d6003ceE245C4997Ff908029aa0116177b69`  
**Funding Track:** Public Goods, DePIN / Open Hardware, Regenerative Finance (ReFi)  
**Requested Amount:** 1 – 3 ETH (Retroactive / Milestone Builder Grant)

---

## 1. Executive Summary

**KuifiMapu** ("Ancient Land" in Mapudungun) is an independent grassroots open-hardware and regenerative agriculture initiative based in the Global South (Chile). 

We bridge **ancestral indigenous ecological wisdom** with **low-cost open hardware (ESP32 microcontrollers, solar energy, and IoT sensors)** to build affordable, climate-resilient micro-greenhouses and automated water-conservation systems for underprivileged rural and semi-urban communities.

By leveraging **Base Layer 2**, KuifiMapu enables tamper-proof, ultra-low-cost on-chain environmental attestation (logging soil moisture, solar generation, and biodiversity telemetry directly on-chain), turning humble family micro-farms into verifiable DePIN environmental nodes.

---

## 2. The Problem We Are Solving

1. **High Barriers in Precision Agriculture:** Commercial agricultural IoT systems cost thousands of dollars, making automated irrigation and climate monitoring inaccessible to subsistence farmers and small-scale growers.
2. **Water Scarcity & Climate Change:** In drought-stricken rural areas of the Global South, over-irrigation wastes scarce water, while under-irrigation destroys crops.
3. **Loss of Medicinal Biodiversity & Indigenous Knowledge:** Ancestral cultivation techniques and native medicinal plants are disappearing due to lack of documentation and economic hardship.
4. **Extreme Resource Scarcity for Builders:** This project is built entirely by a self-taught neurodivergent developer operating in extreme hardship, caring for an ailing elderly mother, working on a repaired laptop held together by drywall screws, with recycled wires and reclaimed plumbing fittings.

---

## 3. The Technical Architecture on Base L2

```
  +-------------------------------------------------------------+
  |                   KUIFIMAPU FIELD HARDWARE                  |
  |  • ESP32 Microcontroller (Wi-Fi / LoRa)                     |
  |  • Capacitive Soil Moisture Sensors (v1.2)                  |
  |  • 12V Solar Panel + LiFePO4 Battery                        |
  |  • Low-power Solenoid Gravity Drip Valves                   |
  +-------------------------------------------------------------+
                                |
                                v
  +-------------------------------------------------------------+
  |              TELEMETRY AGENT / BASE L2 ORACLE               |
  |  • Lightweight Python / C++ Gateway                         |
  |  • Generates periodic cryptographic hash of hourly telemetry|
  +-------------------------------------------------------------+
                                |
                                v
  +-------------------------------------------------------------+
  |                   BASE LAYER 2 CONTRACT                     |
  |  • On-chain registry of environmental state                 |
  |  • Gas cost: < $0.005 USD per attestation                   |
  |  • Public verifiable record of water conservation & growth  |
  +-------------------------------------------------------------+
```

* **Microcontroller:** Open-source ESP32 firmware running automated drip-irrigation logic based on real-time soil resistance and temperature thresholds.
* **Base Integration:** Utilizing Base's sub-cent transaction fees to anchor verifiable soil moisture and solar energy production hashes on-chain without prohibitive gas costs.
* **Zero Proprietary Lock-In:** All schematics, code, and 3D-printable or recycled component guides are released under open-source MIT / CC-BY-SA licenses.

---

## 4. Current Real Progress & Field Evidence

Unlike theoretical whitepapers, KuifiMapu is physically deployed on the ground:
* **Active Bio-Connected Greenhouse:** Operational wooden nursery with automated solenoid valve, drip tubing, and seedling beds.
* **Germination Trays:** Over 500 seedlings of native herbs and vegetables cultivated under real micro-irrigation.
* **Repaired Field Station:** Real developer workstation operating under extreme physical constraints, documented publicly in the GitHub repository photos.
* **Public Documentation:** Complete bilingual manifesto and photo gallery available at:  
  [https://github.com/KuifiMapu/KuifiMapu#real-progress--field-photos](https://github.com/KuifiMapu/KuifiMapu#real-progress--field-photos)

---

## 5. Budget Allocation & Impact

Every Wei from a Base Builder Grant goes directly into real-world impact and human survival:

| Category | Description | Allocation (%) |
| :--- | :--- | :--- |
| **Household & Caregiver Stability** | Vital medical treatment, medication, and food security for the builder's ailing mother, ensuring the founder has the mental bandwidth and physical stability to build full-time. | 45% |
| **Hardware & Lab Infrastructure** | Replacing the damaged work laptop, purchasing reliable soldering gear, solar charge controllers, and sensor batches for 5 community testbeds. | 35% |
| **Base L2 On-Chain Deployment** | Deploying the production telemetry registry contracts on Base Mainnet, gas sponsorship, and building a lightweight web dashboard. | 20% |

---

## 6. Commitment & Values

We do not build for financial speculation or corporate recognition. We build because technology must be humble, responsible, and aligned with nature. A grant from Base is not just funding for code; it is a lifeline that transforms an indigenous-inspired grassroots micro-farm into a beacon of open-source resilience on Base.

**Builder Contact & Links:**
* **GitHub:** [https://github.com/KuifiMapu](https://github.com/KuifiMapu)
* **Giveth:** [https://giveth.io/project/kuifimapu:-ancestral-wisdom-low-cost-iot-a-home-for](https://giveth.io/project/kuifimapu:-ancestral-wisdom-low-cost-iot-a-home-for)
* **Wallet:** `0x2821d6003ceE245C4997Ff908029aa0116177b69`
