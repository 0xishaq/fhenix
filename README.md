<h1 align=center>Fhenix Onchain Task</h1>

![GYB2KYOXkAACMg0](https://github.com/user-attachments/assets/b16c4bef-f6e8-4cd0-b601-56a16b4ee71c)

## Join Discord
- Jika belum gabung dengan discord fhenix silahkan gabung dulu di sini :  https://discord.gg/2ah76D2Q
- Masuk ke channel `#🤖|bot-commands` selanjutnya ketik `/quests` dan pilih nomor quest untuk deploy
- Task deploy `2`,`8`

![Screenshot 2024-10-24 224102](https://github.com/user-attachments/assets/7f1cf4d0-08bc-4196-894b-35da48ad3459)

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

![Screenshot 2024-10-24 224801](https://github.com/user-attachments/assets/037ca742-40b5-46e8-ae1d-7ea71f5104fb)
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
- Click ikon `Solidity Compiler` kemudian compile file yang barusan kalian bikin lalu klik compile

![Screenshot 2024-10-24 224857](https://github.com/user-attachments/assets/e9e75522-e197-406a-82a4-feaa3d623253)
- Selanjutnya ubah chain dari wallet kalian ke `Fhenix Helium`
- Pilih `Injected Provider` kemudian Connect wallet kalian ke remix
- Kemudian click `Deploy` untuk mendeploy contract
- Approve tx di wallet yang kalian connect ke remix

![Screenshot 2024-10-24 225119](https://github.com/user-attachments/assets/3ae67df0-4506-45a9-8a96-b6f88d8c8dbf)
- Tralala kalian sudah berhasil mendeploy contract di `Fhenix Helium`
- Kalian bisa cek contract yang telah kalian deploy di deployed contract posisi pojok kiri bawah
- Selanjutnya adalah kalian harus membuat 5 contract untuk mendapatkan 150 points
- Untuk mendeploy contract lagi kalian tinggal click `Deploy` lagi sampai 5 contract

## Contract Verification

- Untuk Verif Contract sudah otomatis 
![Screenshot 2024-10-28 233305](https://github.com/user-attachments/assets/2ad5fc7e-a47b-4be3-875d-01f2ee329dbb)

# Submit Task
- Kalian masuk kembali ke channel task kalian terus klik edit jika baru deploy 1 kontrak
- Ingat jangan dulu klik submit jika kalian belum deploy 5 Contract
- Jika sudah 5 contract baru klik submit

![Screenshot 2024-10-28 233355](https://github.com/user-attachments/assets/1d62d143-8db1-409e-a9db-a5898cb585de)
