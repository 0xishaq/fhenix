<h1 align=center>Fhenix Onchain Task</h1>

## Join Discord
- Jika belum gabung dengan discord fhenix silahkan gabung dulu di sini :  https://discord.gg/2ah76D2Q
- Masuk ke channel `#🤖|bot-commands` selanjutnya ketik `/quests` dan pilih nomor quest untuk deploy


## Setup Network
- Visit [Chainlist](https://chainlist.org/?testnets=true&search=Fhenix+Helium)
- Click `Connect wallet` kemudian add network ke wallet yang kalian gunakan

## Faucet tFHE(bridge)
- Kalian bisa klaim faucet di discord
- Kalian juga bisa mendapatkan faucet dengan cara bridge dari sepolia menggunakan website berikut

1. [Native Bridge](https://bridge.helium.fhenix.zone/)
2. [Pheasant Bridge](https://testnet.pheasant.network/)

# Deploy the Smart Contract
- Visit [Remix Ethereum](https://remix.ethereum.org/)
- Bikin File `.sol` baru kasih nama bebas misal `haq.sol`
- Copy script berikut
```bash
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.26;

contract SimpleStorage {
    uint256 public storedData;

    function set(uint256 x) public {
        storedData = x;
    }

    function get() public view returns (uint256) {
        return storedData;
    }
}
```
- Click ikon `Solidity Compiler` kemudian compile file yang barusan kalian bikin
- Selanjutnya ubah chain dari wallet kalian ke `Fhenix Helium`
- Pilih `Injected Provider` kemudia Connect wallet kalian ke remix
- Kemudian click `Deploy` untuk mendeploy contract
- Tralala kalian sudah berhasil mendeploy contract di `Fhenix Helium`
- Kalian bisa cek contract yang telah kalian deploy disini
- Selanjutnya adalah kalian harus membuat 5 contract untuk mendapatkan 150 points
- Untuk mendeploy contract lagi kalian tinggal click `Deploy` lagi sampai 5 contract

## Contract Verification

- Untuk Verif Contract sudah otomatis 


# Clear Task
