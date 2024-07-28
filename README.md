# NFT Minting DApp

Bu proje, kullanıcıların cüzdanlarını bağlayarak bir görsel yüklemesini ve bu görselin NFT'sini oluşturup mint etmesini sağlayan basit bir DApp (Decentralized Application) uygulamasıdır.

## Özellikler

- Kullanıcılar cüzdanlarını bağlayabilir.
- Görsel dosyaları yükleyebilir.
- Yüklenen görseller Pinata IPFS kullanılarak yüklenir.
- Yüklenen görsellerin IPFS hash'leri kullanılarak NFT mint edilir.

## Gereksinimler

- [Node.js](https://nodejs.org/)
- [MetaMask](https://metamask.io/)
- Pinata API anahtarları (API Key ve Secret API Key)

## Kurulum

1. **Proje dosyalarını klonlayın:**

    ```bash
    git clone https://github.com/YOUR_GITHUB_USERNAME/nft-minting-dapp.git
    cd nft-minting-dapp
    ```

2. **Gerekli bağımlılıkları yükleyin:**

    ```bash
    npm install
    ```

3. **HTML, CSS ve JavaScript dosyalarını yapılandırın:**

    - `index.html`, `styles.css` ve `app.js` dosyalarını düzenleyin.
    - `app.js` dosyasına kontrat adresinizi ve ABI'nizi ekleyin.
    - Pinata API anahtarlarınızı `app.js` dosyasına ekleyin.

4. **Yerel sunucuyu başlatın:**

    ```bash
    npx http-server
    ```

5. **Tarayıcıda yerel sunucuya gidin:**

    ```text
    http://localhost:8080
    ```

## Kullanım

1. **Cüzdanı Bağlayın:**
   - "Connect Wallet" butonuna tıklayarak MetaMask cüzdanınızı bağlayın.

2. **Görsel Yükleyin:**
   - "Choose File" butonuna tıklayarak bir görsel dosyası seçin.

3. **NFT Mint Edin:**
   - "Mint NFT" butonuna tıklayarak NFT mint işlemini başlatın.

## Proje Hakkında

Bu proje, Solidity ile yazılmış basit bir ERC-721 kontratını kullanarak NFT mint işlemini gerçekleştirmektedir. Görseller, merkeziyetsiz depolama ağı olan IPFS üzerinde saklanmakta ve Pinata API kullanılarak yüklenmektedir. Web3.js kütüphanesi, Ethereum blokzinciri ile etkileşimi sağlar ve MetaMask cüzdanı ile bağlantı kurar.

## Lisans

Bu proje MIT lisansı ile lisanslanmıştır.
