


# 🤖 Mavryk DeFi Automation Bot v1.0

Bot otomatis berbasis Node.js untuk menjalankan berbagai operasi DeFi di jaringan **Mavryk AtlasNet** menggunakan Taquito SDK.

---

## 🔒 Private Project Notice

📌 Script ini dibuat untuk penggunaan **pribadi dan terbatas**.  
Jika kamu tertarik atau ingin tahu lebih lanjut, silakan **DM saya secara langsung**.
> 👉 [https://t.me/FxcTe](https://t.me/FxcTe)

---

## ✨ Fitur Utama

- 🔐 Multi-wallet support (berbasis `privatekeys.txt`)
- 💧 Tambah likuiditas ke liquidity pool
- 🏦 Pembuatan dan pengelolaan vault
- 💸 Pinjam dan bayar MAV secara otomatis
- 📥 Staking token MVN secara langsung
- 🧠 Pengambilan saldo token via TzKT API
- ⚙️ Penjadwalan delay antar langkah & antar wallet

---

## 🚀 Cara Penggunaan

1. **Clone repositori:**
   ```bash
   git clone https://github.com/Boren4anzz/Mavryk-Defi-Automation.git
   cd Mavryk-DeFi-Automation
   ```

2. **Instal dependensi:**

   ```bash
   npm install
   ```

3. **Siapkan file `privatekeys.txt`:**
   Masukkan private key (tanpa tanda kutip) untuk setiap wallet per baris.

4. **Jalankan bot:**

   ```bash
   node main.js
   ```

---

## 🧩 Konfigurasi Penting

Semua konfigurasi utama berada langsung di dalam file `main.js`, seperti:

* **RPC Endpoint:**

  ```js
  const RPC_URL = "https://atlasnet.rpc.mavryk.network";
  ```

* **Alamat Kontrak:** (Vault, Staking, Token)

* **Jumlah likuiditas / staking**

* **Delay antar langkah dan wallet**

---

## 📦 Dependencies

* `@mavrykdynamics/taquito`
* `@mavrykdynamics/taquito-signer`
* `chalk@4`
* `fs`, `path`

---

## 👨‍💻 Credits

Developed with 💙 by [@Boren4anzz](https://github.com/Boren4anzz)
Mavryk Network enthusiast & DeFi automation tinkerer.

---


