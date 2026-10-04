# 🛡️ Swivel Shield

> **A Cash App-inspired payment defense system that stops social engineering scams using real-time AI risk detection, spoken voice warnings, 3-second cooldown locks, and a 24-hour recallable Solana escrow.**

---

## 📌 Project Overview
Link to the project https://ai.studio/apps/a99bab40-4230-4bde-89b1-ce87f0650c6c

**Swivel Shield** is an interactive, real-time behavioral payment fraud defense system built directly on top of a Cash App–inspired peer-to-peer mobile payment interface. 

Designed to disrupt Authorized Push Payment (APP) scams (such as fake bail emergencies, sneaker advance-fee deposits, marketplace traps, or crypto doubling schemes), Swivel Shield interrupts the artificial urgency created by scammers before non-refundable money leaves a user's account.

---

## 🚀 Key Features & Architecture

### 1. Multi-Sensory Behavioral Scam Disruption Engine
* **Real-Time Risk Evaluation**: Analyzes transactions in real time for coercive memo language (*"send now"*, *"emergency"*, *"don't call"*), unverified recipient handles, and high-risk transfer amounts.
* **Auditory Circuit-Breakers**: Plays an automatic spoken voice warning (`warning.mp3`: *"Swivel Shield alert. High scam risk detected..."*) paired with a security chime to break the user out of emotional tunnel vision.
* **Mandatory 3-Second Cognitive Cooldown**: Locks the authorization button behind a compulsory 3-second countdown timer, preventing impulsive, reflexive taps and forcing the user to process the warning signal.

### 2. Reversible Protection: Solana 24h Escrow Alternative
* **On-Chain Safety Net**: When high-risk scams are detected, the app presents a **Solana 24h Protected Escrow Alternative** banner.
* **24-Hour Recall Rights**: Users can deposit funds into a time-locked dispute escrow instead of sending irreversible cash. The recipient is notified, but the sender retains 24-hour recall rights to claw back funds if fraud is confirmed.

### 3. User Autonomy & Override Audit Trail (Route B)
* **Respecting User Control**: If a user ignores the recommended Solana Escrow protection and insists on proceeding with a flagged transaction, the system allows the transfer to go through while generating an explicit audit receipt:
  * **Evaluation Status**: Logs `Route B (High Risk Warning Overridden)`.
  * **Audio & Delay Logs**: Confirms `Played (Circuit-Breaker Triggered)` and `3s Pause Enforced`.

### 4. "Safe Transfer" Mode: Zero Friction Fast-Track (Route A)
* **Uninhibited Everyday Payments**: Proves security does not slow down legitimate users for routine expenses (e.g., paying `$roommate_dan` for tacos).
* **Zero Interstitials & Delays**: Bypasses all security popups, voice alerts, and countdown timers (`Cognitive Delay: 0 seconds`).
* **Green Check Mark End Screen**: Transitions directly to a clean completion screen with a glowing green check mark, emerald confetti, a `✓ Verified Safe Transfer — Zero Friction` badge, and an explanatory receipt note confirming why no warnings popped up.

### 5. Interactive Testing & Documentation
* **Quick Contrast Switcher**: Integrated top-level preset selectors allowing judges and users to toggle between **🟢 Safe (No Warning • Green Check)** and **🔴 Scam (Warning + 3s Pause)** with one click.
* **Comprehensive Architecture**: Complete dual-path user journey maps and comparative test scenarios documented in `IMPLEMENTATION_PLAN.MD`.
