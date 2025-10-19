# OpenMind

![G3Jg94JaUAATMqQ](https://github.com/user-attachments/assets/581c2d46-d082-45b8-a623-777ea4dcc433)

| X        | Minimum              |
|------------------|----------------------------|
| **CPU**          | 12++ |
| **RAM**          | 32++ GB                    |
| **Disk**      | 50 GB+ NVME GB SDD                   |
| **Internet Hızı**      | 1 Gbps+  |
| **Ubuntu**      | Ubuntu 24.04++  |


| Server         | Link              | Features |
|------------------|----------------------------|----------------------------|
| **Contabo**          | [Link](https://www.dpbolvw.net/click-101330552-12454592)                     | Cheap / Paypal  |
| **NetCup**          | [Link](https://www.netcup.com/en/?ref=261820) | Cheap / Paypal |


## Server Güncelleme : 

```bash
sudo apt update -y && sudo apt upgrade -y
```
## Paketleri İndirelim :

```bash
sudo apt install htop ca-certificates zlib1g-dev libncurses5-dev libgdbm-dev libnss3-dev tmux iptables curl nvme-cli git wget make jq libleveldb-dev build-essential pkg-config ncdu tar clang bsdmainutils lsb-release libssl-dev libreadline-dev libffi-dev jq gcc screen file unzip lz4 -y
```

## Ek Paketler ; 

```bash
sudo apt install portaudio19-dev python3-dev ffmpeg -y
```

## UV : 
```bash
curl -LsSf https://astral.sh/uv/install.sh | sh
```
```bash
source ~/.bashrc
```

- Version ile Kontrol ; 
```bash
uv --version
```

<img width="657" height="314" alt="image" src="https://github.com/user-attachments/assets/404a55b9-b380-4ded-adc9-72f8d7551d87" />

## OM1 İndirelim ; 
```bash
git clone https://github.com/openmind/OM1.git
cd OM1
git submodule update --init
uv venv
```

## Venv Akitfleştirelim
```bash
source .venv/bin/activate
```

## OpenMind Api Anahtar

- Link : https://portal.openmind.org/

<img width="1825" height="503" alt="image" src="https://github.com/user-attachments/assets/68b53528-71d5-47ff-b98e-8ef1099e2b89" />

- Purchase Credits'den USDC ile bakiye yüklüyorsunuz. 3 USDC Attım ben - ödeme kısmında Crypto ile ödeme var sadece USDC Kabul ediyor bende base ağında usdc olarak ödedim.
- Alttaki Create API Key'e basın key vericek onu kaydedin tek seferlik gözüküyor.
```bash
cp env.example .env
```

```bash
nano .env
```

<img width="1283" height="744" alt="image" src="https://github.com/user-attachments/assets/12d37aa7-6a58-4c2e-b64d-95952b4f4df3" />

- OM_API_KEY=senin_api_keyin_buraya
- Sonrasında CTRL X CTRL Y Enter.  Kaydeilecek.
