# 🚀 GpuMiner — Efficient GPU-Based Miner for Kaspa (KHeavyHash)

GpuMiner is a lightweight and efficient GPU mining software designed specifically for mining Kaspa (KAS) cryptocurrency using the KHeavyHash algorithm. This miner is optimized for NVIDIA GPUs and supports multiple pool connections with TLS encryption, providing a secure and stable mining experience.

# ✨ Features
⚙️ Supports KHeavyHash Algorithm — optimized for mining Kaspa efficiently.
🎮 NVIDIA GPU Support — compatible with most modern NVIDIA GPUs.
🔒 Stratum and Stratum+TLS Protocols — connect securely to mining pools.
📈 Real-Time Stats — live monitoring of hashrate, shares, GPU temperature, and more.
🛡️ Automatic Reconnection — ensures continuous mining in case of connection drops.
🌐 Multi-Pool Support — mine on any Stratum-compatible Kaspa pool.
⚡ Low Resource Usage — lightweight and efficient for maximum mining performance.

## Requirements

- **NVIDIA GPU** (Recommended: GTX series and above, but supports low-end like MX series for learning purposes)
- **NVIDIA drivers** properly installed
- **Windows environment** (tested on Windows 10/11)
- **Internet connection** for pool mining

## Usage

1. **Download the latest version** of the GpuMiner executable (`.exe`) from the [Releases](https://github.com/adamgaafar/GpuMiner/releases) section.
   
2. **Run the miner** with your Kaspa wallet address and desired pool.

### Getting Started with Kaspa Mining

#### 1. Create a Kaspa Wallet
   - Go to the official [Kaspa Wallet page](https://kaspa.org) to create a Kaspa wallet.
   - Follow the instructions on the website to set up your wallet and generate your unique wallet address.
   - This wallet address will be used to identify your mining rewards.

#### 2. Select a Mining Pool

   - Visit [Kaspa Pool](https://kaspa-pool.org/#/start_mining) to choose a mining pool.
   - On the **Start Mining** page, you will find the details you need to configure your miner, such as:
     - **Pool Address** (server URL)
     - **Port** (usually 5555 for most pools)
     - **Username** (Your Kaspa wallet address)
     - **Password** (usually set to `x` by default or as specified by the pool)

#### 3. Get the Server Address and Port

   - Go to [Kaspa Pool](https://kaspa-pool.org/#/start_mining).
   - Under **Start Mining**, you’ll see a sample mining configuration with details like:
     
     ```bash
     GpuMiner.exe --algo kheavyhash --server <POOL_ADDRESS> --port <POOL_PORT> --user kaspa:<YOUR_WALLET_ADDRESS> --pass x
     ```

     **Example:**
     - **Server**: `eu1.kaspa-pool.org`
     - **Port**: `5555`
     - **Your Wallet Address**: Replace `<YOUR_WALLET_ADDRESS>` with the address you received from your Kaspa wallet.

#### 4. Start Mining

   - Once you have your wallet address and pool configuration, you can start mining by running the miner.

   Example:
    Run the exe or appimage(Linux) enter your wallet address and server pool

# 🚧 Requirements
✅ NVIDIA GPU (Recommended: GTX series and above, but supports low-end like MX series for learning purposes)
✅ NVIDIA drivers properly installed
✅ Linux environment (tested on Ubuntu)
✅ Internet connection for pool mining

💡 Notes
# ⚠️ Monitor GPU temperatures to avoid overheating.
✅ Mining results and earnings will be reflected in your pool dashboard after successful share submissions.
💰 Payouts depend on pool's payout policy (check pool's minimum threshold).
