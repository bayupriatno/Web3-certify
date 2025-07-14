

---

🧾 Prompt Proyek – Web3 Sertifikat Digital NFT

Buatkan saya aplikasi web3 berbasis Next.js (App Router + TypeScript + Tailwind CSS) yang memungkinkan admin (lembaga pelatihan/sekolah) untuk menerbitkan sertifikat digital sebagai NFT ke blockchain.

Fitur utama:
- Halaman dashboard admin untuk input nama peserta & judul sertifikat
- Upload gambar sertifikat (opsional) dan simpan metadata ke IPFS
- Integrasi wallet (Metamask) menggunakan Wagmi + RainbowKit
- Mint NFT ke wallet peserta menggunakan smart contract ERC-721
- Tampilkan halaman verifikasi publik (berdasarkan tokenId atau txHash)
- Gunakan Supabase untuk menyimpan data metadata off-chain
- Gunakan jaringan Polygon Mumbai (testnet)
- Smart contract menggunakan Solidity (ERC-721 dengan URI)
- Sertifikat disimpan di IPFS via Web3.storage

Struktur proyek:
- `app/` dengan routing App Router
- Halaman: `/`, `/mint`, `/verify/[id]`, `/dashboard`
- Gunakan .env untuk menyimpan API key (Web3Storage, Alchemy, dll)
- Tambahkan README dan .env.local.example

Tujuan proyek ini adalah membuat sistem sertifikasi digital yang transparan, tidak bisa dipalsukan, dan bisa diverifikasi publik secara on-chain. Sertifikat akan berupa NFT yang bisa dibuka dan diverifikasi melalui link unik.


---
