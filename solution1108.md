# OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能
  - OSI七層簡介
      - 實體層（Physical Layer）
        - 訂定電腦連接的電氣特定協定 
      - 資料鏈結層 (Data-Link Layer)
        - 訊框 (frame) 與實體位置 (MAC)
      - 網路層 (Network Layer)
        - 邏輯定址
      - 傳輸層 (Transport Layer)
        - 提供可靠或不可靠的遞送，重傳之前先校正錯誤    
      - 交談層 (Session Layer)   
        - 負責建立、管理、以及終止兩個通訊主機的對話
      - 表現層 (Presentation Layer)
        - 處理不同資料格式之間的字碼轉換及編碼及解碼
      - 應用層 (Application Layer)
        - 提供使用者介面  
## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy

## TCP/IP有那些層?寫出與OSI七層模型的對應!

## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
    - HyperText Transfer Protocol 超文本傳輸協定
    - HTTP CacheCache 對網站速度很重要。 此文章描敘不同的方法使用 HTTP Header 控制它。
    - HTTP 的演化 (en-US) HTTP 早期版本變化的簡要說明，到現在的 HTTP/2 與其他版本。。
  - HTTPS
    - 超文本傳輸安全協定（HyperText Transfer Protocol Secure，HTTPS；
    - 常稱為HTTP over TLS、HTTP over SSL或HTTP Secure
    - HTTPS的信任基於預先安裝在作業系統中的憑證頒發機構（CA）。
    - HTTPS的主要作用是在不安全的網路上建立一個安全信道，並可在使用適當的加密套件和伺服器憑證可被驗證且可被信任時，對竊聽和中間人攻擊提供合理的防護。
    - HTTPS開發的主要目的，是提供對網站伺服器的身分認證，保護交換資料的隱私與完整性。
- DNS vs DNSsec
  - DNS
    - 網域名稱系統（英語：Domain Name System，縮寫：DNS）是網際網路的一項服務。
    - 授權 DNS 服務︰授權 DNS 服務提供一種更新機制，供開發人員用於管理其公有 DNS 名稱。  
  - DNSsec
    - 域名系統安全擴充（英語：Domain Name System Security Extensions，縮寫為DNSSEC）
    - 是Internet工程任務組 （IETF）的對確保由域名系統 （DNS）中提供的關於網際網路協定（IP）網路使用特定類型的資訊規格套件。  
- telnet vs ssh
  - telnet
    -  Telnet是一種應用層協議，使用於網際網路及區域網中，使用虛擬終端機的形式，提供雙向、以文字字串為主的命令列介面互動功能。
    -  Telnet在1969年開發出來，在RFC 15定義，RFC 854定義了擴充功能。
  - ssh
    - 安全外殼協定（Secure Shell Protocol，簡稱SSH）是一種加密的網路傳輸協定，可在不安全的網路中為網路服務提供安全的傳輸環境。
    - SSH通過在網路中建立安全隧道來實現SSH客戶端與伺服器之間的連接。   
- ftp vs sftp
  - ftp
    - FTP(File Transfer Protocol) 檔案傳輸協定，用於網際網路上，用戶端與伺服器之間進行檔案傳輸的應用層協定。  
  - sftp
    - SFTP（安全檔案傳輸協定）是一種檔案傳輸協定，它利用一組公用設施，為遠端電腦提供安全訪問，以提供安全通信。許多人認為它是安全文件傳輸的最佳方法。
- smtp, pop3
  - smtp
    - 簡單郵遞傳送協定（英語：Simple Mail Transfer Protocol，縮寫：SMTP）可用在傳送和接收電子郵件的資訊，但SMTP通常用作傳送電子郵件資訊，而不是接收。
  - pop3
    - POP3的全名是Post Office Protocol – Version 3。   
- SNMP
  - SNMP
    - 簡單網路管理協定（SNMP，Simple Network Management Protocol）構成了網際網路工程工作小組（IETF，Internet Engineering Task Force）定義的Internet協定族的一部分。

## 簡述底下傳輸層協定(英文全名與簡單功能說明):
- TCP
  - reliable(可靠的) vs unreliable(不可靠的)
  - TCP three-way handshaking(三項交握)  
  - TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明):
- IP
- ICMP
