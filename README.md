<h1 align="center"> Manta Network </h1>

![image](https://user-images.githubusercontent.com/101149671/195413725-5104a7f2-83b9-4c41-ad42-f91c51abbb0d.png)

## System Requirements:
```
2GB RAM
2 CPU
50GB SSD
```

* Team Announcement: You're eligible for a special NFT for everyone who joins, and a special title on our official Discord Channel
 * Discord [Link](https://discord.gg/yBkpZT8u)
 
 ## Setup:
```
sudo apt update
```

```
sudo apt install pkg-config build-essential libssl-dev curl jq
```

```
curl https://sh.rustup.rs/ -sSf | sh -s -- -y
```

```
source $HOME/.cargo/env
```

```
git clone https://github.com/Manta-Network/manta-rs.git
```

```
cd manta-rs
```

```
cargo run --release --package manta-trusted-setup --all-features --bin groth16_phase2_client register
```

## After the installation is complete, we enter our twitter and e-mail address and save the output.


##  After we get the printout, we fill out the form.: [Link](https://mantanetwork.typeform.com/TrustedSetup)

* It must be exactly the same as the information entered into the server and given in the output.
 * The form will ask for a KMA address, polkadot wallet is on the top right we choose the calamari address from the settings.
 
 ![Ekran görüntüsü 2022-10-21 181902](https://user-images.githubusercontent.com/69756547/197230840-5a3ee46c-cfa8-4734-a77b-fb1f81202f4d.png)
 



