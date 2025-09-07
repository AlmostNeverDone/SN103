# RSA and DSA Public Key Cryptography Practice
RSA 與 DSA 公開金鑰密碼學實作

---------

<h2>Outline 簡介</h2>

This project explores the implementation of public-key cryptography using the OpenSSL toolkit, covering RSA and DSA key generation, encryption and decryption, signing, and verification, as well as the application of hashing before signing.

本專案探索使用 OpenSSL 工具包實現公鑰加密，涵蓋 RSA 和 DSA 金鑰生成、加密和解密、簽署和驗證，以及簽署前雜湊演算法的應用。

Through this practical implementation, we will gain an understanding of the role of public-key cryptography in data protection, integrity verification, and non-repudiation, laying the foundation for further study of SSL/TLS and PKI architectures.

透過本次實踐，我們將了解公鑰加密在資料保護、完整性驗證和不可否認性方面的作用，為進一步研究 SSL/TLS 和 PKI 架構奠定基礎。

---------
<h2>Objectives 目標</h2>

* Demonstrate the generation, encryption/decryption, and signing/verification using RSA.<br/>
  (展示 RSA 金鑰生成、加解密與簽章驗證)</b>
  <br/>

* Explore the use of DSA as another public key cryptography algorithm.<br/>
  (探索 DSA 演算法)</b>
  <br/>

* Understand the importance of hashing before signing and how digital signatures ensure data integrity.<br/>
  (理解簽章前雜湊的重要性，確保資料完整性)</b>
  <br/>


---------

<h2>Tools and Concepts Covered 涵蓋工具與概念</h2>

<div align="center">
</p>

| Aspect <br/>(面向)                          | Learning content and purpose <br/>(學習內容與目的)                                                    |
| ----------------------------------------- | ---------------------------------------------------------------------------------------------- |
| Key Management <br/>(金鑰管理)                | Generate RSA and DSA private/public key pairs. <br/>(生成 RSA 與 DSA 公私鑰)                         |
| Encryption/Decryption <br/>(加解密)          | Encrypt and decrypt files using RSA public/private keys. <br/>(使用 RSA 公私鑰加解密檔案)                |
| Digital Signature <br/>(數位簽章)             | Sign with private keys and verify with public keys. <br/>(以私鑰簽章並以公鑰驗證)                         |
| Hashing before Signing <br/>(雜湊與簽章)       | Combine hashing (SHA1) with RSA signing. <br/>(結合 SHA1 雜湊與 RSA 簽章)                             |
| Practical Security Thinking <br/>(資安實務思維) | Understand authenticity and integrity through cryptographic workflows. <br/>(透過密碼學流程理解真實性與完整性) |
</div>


---------


<h2>Materials and Methods 材料與方法</h2>

[Environment]
* Oracle VM VirtualBox (VirtualBox 虛擬機)</b>
* Kali Linux OS (Kali Linux 作業系統)</b>

[Tasks]
* RSA Key Pair Generation (RSA 金鑰生成)</b>
* RSA Encryption and Decryption (RSA 加解密)</b>
* RSA Signing and Verification (RSA 簽章與驗證)</b>
* DSA Key Pair Generation (DSA 金鑰生成)</b>
* Hashing before Signing (簽章前雜湊)</b>

---------

<h2>Practice 實踐</h2>

<p align="center">
<b>Task 1-1: Generate Private Key & Extract Public Key<br/>(產生私鑰並提取公鑰)</b><br/>
<img src="https://i.imgur.com/TH4DGYh.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 1-2: View Private Key Details <br/>(檢視私鑰)</b><br/>
<img src="https://i.imgur.com/2A5KA6m.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 1-3: View Public Key in ASN.1 Format<br/>(檢視公鑰 ASN.1 格式)</b><br/>
<img src="https://i.imgur.com/r2IKqo1.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* Display the random number in Hexadecimal 2-byte units.<br/>(以十六進位2位元組為單位顯示隨機數)</b>
<br />
<br />
<b>Task 4: Automate with Bash Script<br/>(使用 Bash 腳本自動化)</b><br/>
<img src="https://i.imgur.com/23mfFYL.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
* This script automates random key generation and prints the result in hex.<br/>(此腳本自動產生隨機金鑰並以十六進位輸出結果)</b>
<br/>


---------

<h2>Results 成果展示</h2>

Through this project, we practiced using OpenSSL for cryptographic operations. The steps covered installation verification, algorithm exploration, random key generation, and automation with Bash scripting. This practical knowledge is useful for understanding fundamental cryptographic processes and applying them in real-world system security contexts.

透過本次專題，我們熟悉了使用 OpenSSL 進行加密作業的流程。步驟涵蓋了安裝驗證、演算法探索、隨機金鑰生成，以及使用 Bash 腳本自動化的應用。這些實務技能有助於理解基礎加密流程，並在實際資訊安全情境中加以應用。


---------

<h2>Reference 參考</h2>

[UniSQ] [CSC8520 - Securing Networks](https://handbook-guide.unisq.edu.au/course/2025/CSC8520)
<br/>
