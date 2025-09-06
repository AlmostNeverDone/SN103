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

* Verify installation and environment.<br/>
  (確認安裝環境與 OpenSSL 版本)</b>
  <br/>

* Explore supported algorithms.<br/>
  (探索 OpenSSL 支援的演算法)</b>
  <br/>

* Generate secure random keys.<br/>
  (產生具隨機性的加密金鑰)</b>
  <br/>

* Automate tasks using Bash scripting.<br/>
  (利用 Bash 腳本自動化隨機數產生流程)</b>
  <br/>

* Build hands-on cryptographic understanding.<br/>
  (建立加密作業的實務理解，並為進一步資訊安全研究奠定基礎)</b>
  <br/>

---------

<h2>Tools and Concepts Covered 涵蓋工具與概念</h2>

<div align="center">
</p>

| Aspect <br/>(面向) | Learning content and purpose <br/>(學習內容與目的) |
| ----------------- | ----------------------------------------------- |
| Cryptographic toolkit <br/>(加密工具) | Learn the usage of OpenSSL for cryptographic operations. <br/>(學習使用 OpenSSL 進行加密作業) |
| Algorithm exploration <br/>(演算法探索) | Explore digest and cipher algorithms supported by OpenSSL. <br/>(探索 OpenSSL 支援的雜湊與加密演算法) |
| Random key generation <br/>(隨機金鑰生成) | Generate and view cryptographic random numbers using OpenSSL. <br/>(透過 OpenSSL 產生與檢視隨機金鑰) |
| Automation with scripting <br/>(腳本自動化) | Write a Bash script to automate random number generation. <br/>(撰寫 Bash 腳本以自動化產生亂數金鑰) |
</div>
<br/>

---------


<h2>Materials and Methods 材料與方法</h2>

[Environment]
* Oracle VM VirtualBox (VirtualBox 虛擬機)</b>
* Kali Linux OS (Kali Linux 作業系統)</b>

[Tasks]
* Check OpenSSL Version (檢查 OpenSSL 版本)</b>
* Explore Supported Commands and Algorithms (探索支援的指令與演算法)</b>
* Generate Random Numbers (產生隨機數字)</b>
* Automate with Bash Script (使用 Bash 腳本自動化)</b>

---------

<h2>Practice 實踐</h2>

<p align="center">
<b>Task 1: Check OpenSSL Version<br/>(檢查 OpenSSL 版本)</b><br/>
<img src="https://i.imgur.com/2Sc5HNp.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 2: Explore Supported Commands and Algorithms<br/>(探索支援的指令與演算法)</b><br/>
<img src="https://i.imgur.com/uLQqz29.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
<b>Task 3: Generate Random Numbers<br/>(產生隨機數字)</b><br/>
<img src="https://i.imgur.com/lRJXM0r.jpeg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
