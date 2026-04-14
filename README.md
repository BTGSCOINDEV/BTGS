# 🪙 Bitcoin Gold BTGS (BTGS Core)
**Next-Generation PoW Blockchain | SHA-256 | BTG-20 Inscriptions Support**

---

## 📊 Tokenomics & Supply Metrics
* **Total Max Supply:** 26,000,000 BTGS
* **Developer Fund:** 2,500,000 BTGS (Only **9.6%**) - Reserved for infrastructure, security audits, and ecosystem scaling.
* **Community Allocation:** 23,500,000 BTGS - Distributed via decentralized mining.

## ⚙️ Technical Core
* **Algorithm:** SHA-256 (Industrial-grade security).
* **Protocol:** Native support for **BTG-20** (Inscriptions/Ordinals), allowing decentralized deployment, minting, and transfer of digital artifacts directly on the BTGS blockchain (similar to BRC-20).
* **Infrastructure:** High-performance LevelDB integration for rapid node synchronization and data integrity.

---

## 🛠 Build Instructions (Linux)
Building the node and command-line interface is straightforward. You only need to create a build directory and use CMake.

### **Building `bitcoingoldd` and `bitcoingold-cli`**
1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/BTGSCOINDEV/BTGS.git](https://github.com/BTGSCOINDEV/BTGS.git)
    cd BTGS
    ```

2.  **Configure and Build:**
    ```bash
    mkdir build && cd build
    cmake ..
    make -j$(nproc)
    ```
*The binary files (`bitcoingoldd` and `bitcoingold-cli`) will be located in the `bin/` directory within your build folder.*

---

## 📦 Official Releases
We provide precompiled, stable binaries for all major platforms in the **Releases** section:
* **Linux:** Stable ELF binaries for server environments and node operators.
* **Windows:** Portable and installer versions (`.exe`).
* **GUI Wallets:** Full Qt-based graphical interfaces for both Windows and Linux users.

---

## 🌐 Ecosystem & Community Links

| Resource | Official Links |
| :--- | :--- |
| **ALGORITHM** | [SHA-256](https://en.wikipedia.org/wiki/Secure_Hash_Algorithms) |
| **Official Website** | [btgscoin.site](https://btgscoin.site) \| [bitcoingold.site](https://bitcoingold.site) |
| **Block Explorer** | [explorer.btgscoin.site](https://explorer.btgscoin.site) \| [explore.bitcoingold.site](https://explore.bitcoingold.site) |
| **BitcoinTalk** | [Official BTGS Announcement](https://bitcointalk.org/index.php?topic=5579096.msg66572040#msg66572040) |
| **API** | [API](https://api.bitcoingold.site) |
| **Telegram Group** | [BTGS Community](https://t.me/BitcoinBTGS) |
| **Discord Server** | [Developer & Node Support](https://discord.gg/7wJD7hfGf) |
| **X (Twitter)** | [@BitcoinBTGS](https://x.com/BitcoinBTGS) |

---

## ⚡ Electrum Servers (Infrastructure)
For developers and light-wallet users, our Electrum servers are active and support both encrypted and non-encrypted connections:

* **Host 1:** `electrum.btgscoin.site`
* **Host 2:** `electrum.bitcoingold.site`

**Port Configuration:**
* **TCP Port:** `50001` (Standard)
* **SSL Port:** `50002` (Secure)
* **WSS Port:** `50005` (Secure)


---

## 💡 BTG-20 Protocol
The **BTG-20** protocol is our answer to the growing demand for on-chain data. By leveraging the security of SHA-256, users can "inscribe" data into the BTGS blockchain, creating a permanent, immutable record for tokens and digital art, mirroring the success of BRC-20 on the Bitcoin network.

---

## 📄 License
Bitcoin Gold BTGS is open-source software released under the **MIT License**. See the `COPYING` file for more details.
