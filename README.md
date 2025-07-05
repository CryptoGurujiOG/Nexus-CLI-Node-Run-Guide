# Nexus-CLI-Node-Run-Guide

Earn Nex Points by contributing your computing power to the Nexus network. You can convert your Nex Points into testnet $NEX, which will determine your share of the mainnet $NEX token airdrop.

---

## Can i use multiple devices

- You can use multiple devices like Pc, Laptop, Mobile, Tablets etc
- You can connect all devices with a single Nexus account

---

## Step 1:

- Visit: https://app.nexus.xyz/
- Click on Sign up to earn points
- Create a new account or Log in existing one

- Disable Battery Saver mode
- Start Nexus Browser Node to earn points

Like this 👇

![image alt](https://github.com/CryptoGurujiOG/Nexus-CLI-Node-Run-Guide/blob/c1ab6f23e907ae7da2dbb4f8da994344ea2da3b6/Screenshot%201.png)

## Nexus CLI Node Steps:

- Install WSL using this 👉 [GUIDE](https://github.com/CryptoGurujiOG/Install-Ubuntu-on-Windows-using-WSL)

- Open Ubuntu on your Pc
- Install Dependecies

```
sudo apt update & sudo apt upgrade -y
sudo apt install screen curl build-essential pkg-config libssl-dev git-all -y
sudo apt install protobuf-compiler -y
sudo apt update
```

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

```
source $HOME/.cargo/env
```

```
rustup target add riscv32i-unknown-none-elf
```

## Run Prover

- Start a screen to keep it running in the background

```
screen -S nexus
```

- Install Nexus CLI node
- You can update Nexus node using the same command

```
curl https://cli.nexus.xyz/ | sh
```

- Create Node ID
- Visit: https://app.nexus.xyz/nodes
- Click on Add CLI node
- Copy your Node ID

Like this 👇

![image alt](https://github.com/CryptoGurujiOG/Nexus-CLI-Node-Run-Guide/blob/ee5f6e959ef7c23eb86feff3f79dab432c506180/Screenshot%202.png)

![image alt](https://github.com/CryptoGurujiOG/Nexus-CLI-Node-Run-Guide/blob/049620f22791c78c802443b465100c6bb4b2996d/Screenshot%203.png)

- Run this final command with your Node ID

```
source ~/.bashrc

nexus-network start --node-id YOUR NODE ID
```
- Replace `YOUR NODE ID` with your Node ID

---

## You can purchase Nexus CLI nodes on Nodes Garden

- Follow this 👉 [GUIDE](https://x.com/CryptoGurujiOG/status/1937486680098791932)

---

## FOLLOW, SUBSCRIBE and JOIN TELEGRAM

- Twitter: https://x.com/CryptoGurujiOG
- Youtube: https://www.youtube.com/@CryptoGurujiOG
- Telegram: https://www.telegram.me/cryptogurujiog
