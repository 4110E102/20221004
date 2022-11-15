# OSI 模型與TCP/IP protocal suite

## OSI有七層?簡述其功能:
- 第一層︰
  - 實體層（Physical Layer）
    - 實體層是0與1電子訊號。
  
- 第二層︰
  - 資料連結層（Data Link Layer）
    - 資料連結層是在網路之間建立邏輯連結

- 第三層︰
  - 網路層（Network Layer）
    - 網路層是網路路由及定址的功能

- 第四層︰
  - 傳輸層（Transport Layer）
    - 傳輸層負責電腦整體的資料傳輸及控制。

- 第五層︰
  - 會議層（Session Layer）
    - 負責建立網路連線。

- 第六層︰
  - 展示層（Presentation Layer）
    - 應用層收到的資料後，透過展示層可轉換表達方式，或是處理圖片及其他多媒體檔案。

- 第七層︰
  - 應用層（Application Layer）
    - 應用層主要功能是處理應用程式，進而提供使用者網路應用服務。
    
## 底下網路設備運作在哪一層? Hub, switch, router, L4-switch, proxy
- Hub第一層
- Switch第二層
- Router第三層
- L4-switch第四層
- Proxy第七層
## TCP/IP有那些層?寫出與OSI七層模型的對應!
- 網路存取層 (Network Access Layer) --> 實體層、資料鏈結層
- 網路互連層 (Internet Layer) --> 網路層
- 傳輸層 (Transport Layer) --> 傳輸層
- 應用層 (Application Layer) --> 會議層、表現層、應用層

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
    -  檔案傳輸協定(File Transfer Protocol) 。
    -  讓電子裝置相互傳輸的一組程序或規則。
    -  是 TCP/IP 網路上的裝置用來傳遞檔案的一套規則。
    -  使用網際網路其實就是使用各種不同的協定。
    -  FTP 是用來四處移動檔案的協定。
  - sftp
    -  Secure File Transfer Protocol（安全檔案傳輸協定）
    -  是一種檔案傳輸協定
    -  利用一組公用設施，為遠端電腦提供安全訪問，以提供安全通信。
    -  許多人認為它是安全文件傳輸的最佳方法。
    -  利用 SSH（安全插座殼或安全殼），通常也被稱為 "安全殼檔案傳輸協定"。
- smtp, pop3
  - smtp
    - 簡單郵遞傳送協定
    - Simple Mail Transfer Protocol
    - 可用在傳送和接收電子郵件的資訊
    - SMTP通常用作傳送電子郵件資訊，而非接收。
    - SMTP是一個相對簡單的基於文字的協定。
  - pop3
    - pop最新版本為POP3
    - Post Office Protocol - Version 3
    - 提供了SSL加密的POP3協定被稱為POP3S。
    - 原來是專為在一部電腦上使用而設計的較舊協定。
    - 只支援單向電子郵件同步處理
- SNMP
  - SNMP
    - 簡易網路管理通訊協定 
    - Simple Network Management Protocol 
    - 這項通訊協定就是網路監控與裝置通訊的命脈。
    - SNMP 由一組網路管理標準構成
    - 是網際網路通訊協定套件的其中一項要素
## 簡述底下傳輸層協定(英文全名與簡單功能說明):TCP vs UDP
- TCP vs UDP
  - TCP
    - 傳輸控制協定 
    - Transmission Control Protocol
    - 是一種連接導向的、可靠的、基於位元組流的傳輸層通信協定
    - 由IETF的RFC 793定義。
    - TCP層是位於IP層之上，應用層之下的中間層。
  - UDP
    - 使用者資料包協定
    - User Datagram Protocol
    - 是一個簡單的面向資料包的通信協定，位於OSI模型的傳輸層。
    - 由David P. Reed在1980年設計且在RFC 768中被規範。
    - 典型網路上的眾多使用UDP協定的關鍵應用在一定程度上是相似的。
- reliable(可靠的) vs unreliable(不可靠的)
  - reliable 
    - reliable可靠的
    - TCP 使用序列號來標識數據的每個字節。
    - 第一個字節的序列號由發送器為第一個數據包選擇，該數據包標記為 SYN。
    - 是通過發送方檢測丟失的數據並重新傳輸來實現的。
    - TCP 使用兩種主要技術來識別丟失。重傳超時 (RTO) 和重複累積確認 (DupAcks)。
  - unreliable
    - unreliable不可靠的
    - UDP是一種不可靠的協定
    - 應用程式通常必須容許一些遺失、錯誤或重複的封包。
    - 某些應用程式（如TFTP）可能會根據需要在應用程式層中添加基本的可靠性機制。
    - UDP屬於無連接協定
- TCP three-way handshaking(三項交握)
  - 過程建立一個連接。
  - 在連接建立過程中，很多參數要被初始化。
  - 伺服器端被被動打開以後，客戶端就能開始建立主動打開（active open）。
  - SYN佇列：存放完成了二次握手的結果。 佇列長度由listen函式的參數backlog指定。
  - ACCEPT佇列：存放完成了三次握手的結果。佇列長度由listen函式的參數backlog指定。
- TCP syn flood attack
  - SYN 洪水是一種拒絕服務攻擊形式
  - 攻擊者在該攻擊中快速啟動與服務器的連接，而無需完成連接。
  - 服務器必須花費資源等待半開的連接
  - 會消耗足夠的資源以使系統對合法流量無響應
  - 攻擊者發送的數據包是數據包SYN，是TCP用於建立連接的三次握手的一部分。

## 簡述底下網路層協定(英文全名與簡單功能說明): IP   ICMP
- IP
  - 網際協定
  - Internet Protocol
  - 一種應用於網際網路的電腦網路協定
  - IP位址，一種電腦網路位址
  - 是在 TCP/IP 協定套組中網路層的主要協定

- ICMP
  - 網際網路控制訊息協定
  - Internet Control Message Protocol
  - 是網際網路協定套組的核心協定之一。
  - 它用於網際網路協定（IP）中傳送控制訊息，提供可能發生在通訊環境中的各種問題回饋。
  - ICMP依靠IP來完成它的任務，它是IP的主要部分。
