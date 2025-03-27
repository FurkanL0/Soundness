# Soundness

![1500x500](https://github.com/user-attachments/assets/6411da65-2338-4de9-8ac1-501c845e2a29)

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | x |
| **RAM**          | x GB                     |
| **Storage**      | x+ GB SDD                   |
| **Network**      | 100 Mbps (1 Gbps+ recommended) |

| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Cheap / Crypto Payment |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |

## Project : 
- Twitter : https://x.com/SoundnessLabs
- Discord : discord.gg/qXwDb2X4


## 1. Server Update : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Install Packages:

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## Install Protobuf Compiler

```bash
sudo apt install -y protobuf-compiler
```

## Rust ; 

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

- 1, Enter.

```bash
source $HOME/.cargo/env
```

## Install Soundness

```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

- Install

```bash
source ~/.bashrc 
```


```bash
soundnessup install
```

- Update

```bash
soundnessup update
```

## Wallet Generate

- Crate ; 

```bash
soundness-cli generate-key --name my-key
```

![image](https://github.com/user-attachments/assets/2b4ef606-bf79-410f-9a3d-bd734ca7b9d7)


- Save mnemonic.
- Set a password for your wallet.
- When you type your password on Ubuntu servers, it is not visible.

## Send Public Key ; 
```bash
!access public-key
```
![image](https://github.com/user-attachments/assets/d368c41c-dc3f-4e07-aa50-fef56c2141a2)

![image](https://github.com/user-attachments/assets/040cfbb7-fe7d-4513-8f58-6de1c66a96a5)

- Nice

## Other Commands ; 

- Import ; 
```bash
soundness-cli import-key --name my-key
```

- List Key / wallets ; 

```bash
soundness-cli list-keys
```

- Export Key / wallets ; 

```bash
soundness-cli export-key --name my-key
```



<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>
