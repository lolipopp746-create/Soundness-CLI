# soundness
### Install CLI

```
sudo apt update && sudo apt upgrade -y
sudo apt install openssl libssl-dev pkg-config
```

```
curl -sSL https://raw.githubusercontent.com/soundnesslabs/soundness-layer/main/soundnessup/install | bash
source ~/.bashrc
```

```
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs/ | sh
source $HOME/.cargo/env
```

```
soundnessup install
soundnessup update
```

### Import Old Account

```
soundness-cli import-key --name my-key --mnemonic "Your Pharse"
```

### Create New Key/Pubkey (Data Baru)

```
soundness-cli generate-key --name "my-key"
```
