# OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能:
- 第一層︰
  - 實體層（Physical Layer）
    - 實體層是0與1電子訊號。
  
- 第二層︰
  - 資料連結層（Data Link Layer）
    - 資料連結層主要是在網路之間建立邏輯連結，並且在傳輸過程中處理流量控制及錯誤偵測。

- 第三層︰
  - 網路層（Network Layer）
    - 網路層定義網路路由及定址功能，讓資料能夠在網路間傳遞。

- 第四層︰
  - 傳輸層（Transport Layer）
    - 傳輸層主要負責電腦整體的資料傳輸及控制，是OSI模型中的關鍵角色。

- 第五層︰
  - 會議層（Session Layer）
    - 這個層級負責建立網路連線，等到資料傳輸結束時，再將連線中斷。

- 第六層︰
  - 展示層（Presentation Layer）
    - 應用層收到的資料後，透過展示層可轉換表達方式，或是處理圖片及其他多媒體檔案。

- 第七層︰
  - 應用層（Application Layer）
    - 應用層主要功能是處理應用程式，進而提供使用者網路應用服務。
    
## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
## TCP/IP有那些層?寫出與OSI七層模型的對應!

## 簡述底下應用層協定(英文全名與簡單功能說明):
- HTTP vs HTTPs
  - HTTP
     - 超文本傳輸協定（HyperText Transfer Protocol）
     - 用於分佈式、協作式和超媒體訊息系統的應用層協定。
     - HTTP是全球資訊網的數據通信的基礎。
     - 設計HTTP最初的目的是為了提供一種發布和接收HTML頁面的方法。
     - 透過HTTP或者HTTPS協定請求的資源由統一資源識別碼來標識。
     
  - HTTPS
     - 超文本傳輸安全協定（HyperText Transfer Protocol Secure)。
     - 是一種透過計算機網路進行安全通訊的傳輸協定。
     - HTTPS經由HTTP進行通訊，但利用SSL/TLS來加密封包。
     - HTTPS開發的主要目的，是提供對網站伺服器的身分認證，保護交換資料的隱私與完整性。
     - 這個協定由網景公司在1994年首次提出，隨後擴展到網際網路上。

- DNS vs DNSsec
  - DNS
    -  Domain Name System
    -  網際網路上的都是使用數字找到彼此並互相通訊。
    -  這些數字稱為 IP 地址。
    -  輸入像 example.com 這樣的網域名稱就可以連接到正確的位置。
    -  網際網路 DNS 系統的工作原理和電話簿類似。
   
  - DNSses
    -  域名系統安全擴充(Domain Name System Security Extensions）
    -  是IETF的對確保由域名系統DNS中提供的IP網路使用特定類型的資訊規格套件。
    -  是對DNS提供給DNS客戶端（解析器）的DNS資料來源進行認證。
    -  驗證不存在性和校驗資料完整性驗證，但不提供機密性和可用性。
    -  原始設計不包含任何安全細節。
- telnet vs ssh
  - telnet
    - Telnet是一種應用層協議。
    - 屬於TCP/IP協議族的其中之一。
    - 是網際網路遠端登錄服務的標準協議和主要方式。
    - 常用於伺服器的遠端控制。
    - 在1969年開發出來。
  - ssh
    - Secure Shell，即「安全殼協定」。
    - 一項電腦上的安全協定。
    - 沙姆沙伊赫國際機場的IATA代碼。
    - 制消減雜交（suppression subtractive hybridization）。
    - 由Struts，Spring Framework，Hibernate組成的常見JAVA網上開發框架組合的縮稱。

- ftp vs sftp
  - ftp
    -  檔案傳輸協定。
    -  讓電子裝置相互傳輸的一組程序或規則。
    -  是 TCP/IP 網路上的裝置用來傳遞檔案的一套規則。
    -  使用網際網路其實就是使用各種不同的協定。
    -  FTP 是用來四處移動檔案的協定。
  - sftp
    -  SFTP（安全檔案傳輸協定）
    -  是一種檔案傳輸協定
    -  利用一組公用設施，為遠端電腦提供安全訪問，以提供安全通信。
    -  許多人認為它是安全文件傳輸的最佳方法。
    -  利用 SSH（安全插座殼或安全殼），通常也被稱為 "安全殼檔案傳輸協定"。
- smtp, pop3
- SNMP

## 簡述底下傳輸層協定(英文全名與簡單功能說明):TCP vs UDP
- TCP
  - reliable(可靠的) vs unreliable(不可靠的)
  - TCP three-way handshaking(三項交握)  
  - TCP syn flood attack

## 簡述底下網路層協定(英文全名與簡單功能說明): IP   ICMP
- IP
- ICMP
