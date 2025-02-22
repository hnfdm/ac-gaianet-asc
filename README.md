### Gaianet - Auto Chat

Gaianet Auto Chat adalah bot otomatis yang melakukan auto chat melalui Node ID. Bot ini dirancang untuk memudahkan 
menaikkan throughput/interaksi dengan cepat dan efisien.

### Instalasi

1. Clone repository ini ke lokal Anda:

   ```bash
   git clone https://github.com/hnfdm/ac-gaianet-asc.git
   ```

2. Masuk ke direktori proyek:
   ```bash
   cd ac-gaianet-asc
   ```

3. Install modul yang diperlukan:
   ```bash
   npm i
   ```
   
4. Ganti `<NODE_ID>` dengan Node ID kalian di file `autochat.js`.
5. Ganti `NODE_ID` dengan Node ID kalian di file `multi.js`.

### Cara Penggunaan

1. Jalankan bot dengan perintah berikut:
   
   ```bash
   node autochat.js
   ```

2. Jalankan bot (multi node) dengan perintah berikut:
   
   ```bash
   node multi.js
   ```
### Lightweight Model

1. Qwen 2
   ```bash
   gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/qwen2-0.5b-instruct/config.json
   ```
   
2. Stablelm 2
   ```bash
   gaianet init --config https://raw.githubusercontent.com/GaiaNet-AI/node-configs/main/stablelm-2-zephyr-1.6b/config.json
   ```

### How to Install Node?
- Read [Medium Page](https://medium.com/@amirsohail208/how-to-install-gaianet-node-without-getting-stuck-52a8d1b899ee)

### Acknowledgements
- Inspired by [Node Army](https://github.com/sipalingnode) & [stewartid](https://github.com/dicoderin).
