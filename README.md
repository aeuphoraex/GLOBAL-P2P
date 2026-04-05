# 🌀 GLOBAL-P2P: PHASER-SOVEREIGN
### The Decentralization Engine // Quantum WebOS v3.0
**A standalone, single-file (.html) P2P operating environment with Zero-Infrastructure requirements.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Engine: WASM3](https://img.shields.io/badge/Engine-WASM3-purple.svg)]()
[![Network: WebRTC](https://img.shields.io/badge/Network-WebRTC-cyan.svg)]()
[![Security: ZK--RLN](https://img.shields.io/badge/Security-ZK--RLN-magenta.svg)]()

---

## ◈ OVERVIEW
**GLOBAL-P2P** is a revitalized "Quantum-Punk" WebOS designed for total decentralization. Contained within a single HTML file is a complete suite of peer-to-peer protocols, cryptographic tools, and a simulated WASM runtime. It bypasses traditional server-client architecture by leveraging browser-native technologies—such as WebRTC and MQTT—to create a global, self-healing mesh network.

---

## ⚡ CORE SUBSYSTEMS

### 1. Global Mesh & Sync
* **MQTT Bridge:** Synchronizes global node states via a decentralized broker architecture (WSS).
* **HLC (Hybrid Logical Clock):** Provides causal ordering of events across distributed nodes, mitigating clock drift.
* **DAM Topology:** Implements a Cellular or Flat topology map to optimize message propagation and complexity.

### 2. Networking & Traversal
* **NAT/ICE/STUN:** Real-time NAT classification (Full Cone to Symmetric) and ICE candidate gathering for seamless P2P hole punching.
* **DoH Discovery:** Bootstraps peer discovery using DNS-over-HTTPS TXT record queries.
* **DHT Kademlia:** A Distributed Hash Table simulation for keyspace visualization and decentralized peer lookups.

### 3. Privacy & Security
* **E2E Encryption:** AES-256-GCM session encryption with ECDH P-256 key exchange and active rotation.
* **ZK-RLN (Zero-Knowledge Rate Limiting):** Prevents Sybil attacks and spam by requiring ZK-proofs for message broadcasting without compromising anonymity.
* **MASQUE_NOISE:** Injects obfuscated traffic frames to thwart Deep Packet Inspection (DPI) via noise injection.

### 4. Virtualization & Storage
* **WASM3 Core:** A high-performance meta-machine interpreter simulation for executing cryptographic modules like ML-KEM-768 and BLAKE3.
* **OPFS Storage:** Utilizes the Origin Private File System for block-level, high-speed persistent data storage and delta-syncing.

---

## 🛠 TECHNICAL SPECIFICATIONS

| Component | Technology | Implementation |
| :--- | :--- | :--- |
| **Runtime** | WASM3 Meta-Machine | Register-file interpreter simulation |
| **Messaging** | Pub/Sub + Gossip | MQTT + Epidemic Propagation |
| **Cryptography** | Quantum-Resistant | ML-KEM-768 / ED25519 / AES-GCM |
| **Persistence** | OPFS | Delta-sync & Snapshotting |
| **Interface** | CRT/Matrix Hybrid | Canvas-based rendering with Glitch FX |

---

## 🚀 GETTING STARTED

Because the engine is **Phaser-Sovereign** (Standalone), there are no dependencies to install.

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/aeuphoraex/GLOBAL-P2P.git](https://github.com/aeuphoraex/GLOBAL-P2P.git)
    ```
2.  **Launch:**
    Open `GLOBALCHAT-BETA.html` in any modern evergreen browser (Chrome, Brave, Edge, Firefox).
3.  **Boot Sequence:**
    Allow the kernel to initialize subsystems (WASM Decoding → ICE Gathering → ZK Proof Generation).

---

## 📟 APPLICATION SUITE
The OS comes pre-loaded with several "Quantum Apps" accessible via the **Desktop** or **Start Menu**:

* 💬 **MESH_CHAT:** The primary global communication terminal with E2E and ZK support.
* 🛡️ **CORE_SYNC_ZK:** Manage HLC synchronization and monitor ZK-RLN nullifiers/violations.
* 📡 **NAT_ICE_STUN:** Real-time network diagnostic, NAT classification, and peer mapping.
* ⚙️ **WASM3_CORE:** Monitor engine heap, stack, and opcode fusion performance.
* 💾 **OPFS_STORAGE:** Manage block-level delta logs, speed, and snapshots.

---

## 🌌 THE STACK
* **Frontend:** HTML5, CSS3 (Custom CRT/Scanline Overlays), Vanilla JavaScript.
* **Visuals:** Multi-canvas rendering for Matrix rain, DHT rings, and Noise waves.
* **P2P Library:** `mqtt.min.js` (MQTT over WebSockets) + WebRTC DataChannels.

---

## ⚖ LICENSE
Distributed under the **MIT License**. See `LICENSE` for more information.

---
**SYSTEM STATUS:** `MESH ONLINE` // **NODE:** `NEXUS_ADMIN` // **KERNEL:** `v3.0-SOVEREIGN`
