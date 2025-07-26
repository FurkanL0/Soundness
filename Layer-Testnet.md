# Soundness

![1500x500](https://github.com/user-attachments/assets/6411da65-2338-4de9-8ac1-501c845e2a29)


| Server Provider        | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **PQ**      | [Link](https://pq.hosting/?from=627713)                  | Cheap / Crypto Payment |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |

## Proje Sosyal Medyaları : 
- Twitter : https://x.com/SoundnessLabs
- Discord : https://discord.gg/qXwDb2X4


## 1. Sunucu Güncelleme : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## 2. Paketleri İndirme :

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## Protobuf Compiler İndiriyoruz

```bash
sudo apt install -y protobuf-compiler
```

## Rust ; 

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
```

- 1, Enter'e bas hocam

```bash
source $HOME/.cargo/env
```

## Soundness İndirme

```bash
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
```

- İndirme

```bash
source ~/.bashrc 
```


```bash
soundnessup install
```

- Güncelleme

```bash
soundnessup update
```

## Oluşturduğumuz Cüzdanı İçeri Atma ; 

- Cüzdan İçeri Aktarma Komutu ; 

```bash
soundness-cli import-key --name my-key --mnemonic "cüzdankelimeleriniz"
```

<img width="1585" height="153" alt="image" src="https://github.com/user-attachments/assets/8da4ce9b-15cc-4fb5-9a3e-f965ef4ccd38" />


- Cüzdan için bir şifre isteyecek - unutmayacağınız bir şifre olsun.

#### Proof ; 

- Discord'da size botun verdiği CLI mesajını kopyalayın. Cüzdan ismi soruyor ok ile gösterdiğim kısımda. Oraya my-key yazın.

<img width="643" height="347" alt="image" src="https://github.com/user-attachments/assets/df1214a9-0fdc-4922-a4bf-6126a9091802" />

- Örnek ; 

<img width="922" height="110" alt="image" src="https://github.com/user-attachments/assets/e6c274e3-6cc4-441d-9962-2c87d7682f45" />

- Sonrasında Komutu Yapıştırıp Enterleyin.

<img width="663" height="349" alt="image" src="https://github.com/user-attachments/assets/b7b689ea-1fe4-469a-9d81-d05056c074fa" />

- Sucsess Mis Gibi.


#### Key Store Dosyası Kaydedin.

- Sunucuya SFTP ile bağlanın.

<img width="954" height="231" alt="image" src="https://github.com/user-attachments/assets/b298c057-ce3a-4e45-b687-152dd88ad901" />

- Key Store Dosyasını bilgisayarınıza kaydedin önemli.

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=FurkanL0&style=flat-square&color=red&label=Profile+Views+/+Repo+Views+" alt="Repo / Profile Views" />
</p>
