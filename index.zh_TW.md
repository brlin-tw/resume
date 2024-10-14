---
title: 林博仁的履歷
layout: default
description: 為潛在僱主的人力資源評估提供必要資訊
lang: zh-TW
---

{% include navigation.html %}

## 基本資料

* 國立台灣海洋大學資訊工程學系肄業(2010~2018)，修讀期間於下列領域有所成就：
    + 程式語言
    + 作業系統
    + 嵌入式系統
* 現居台灣台北

## 經驗概敘

### 資訊科技

* _熟悉_ 基於 RedHat/Debian 之 **Linux 作業系統**的使用經驗，包含但不限於下列操作：
    + 日常使用（桌面、命令列界面）
    + 系統管理（軟體管理、儲存管理、網路設定）
    + 軟體開發
    + 問題排除
* _熟悉_ 使用 **Git 版本控制系統**，包含但不限於以下操作：
    + 部份文件變更提交  
      `git add --patch`
    + 分支變更基底  
      `git rebase --interactive _base_`
    + Regression 引入版本二元搜尋  
      `git bisect [start|bad|good|...]`
* _熟悉_ 自由與開放來源碼軟體(FOSS)的**開發流程**與**除錯方式**，包含但不限於：
    + 最小化問題重現步驟實作
    + 完整<ruby>呼叫追蹤<rp>(</rp><rt>call trace</rt></ruby>的產生
    + 軟體缺陷報告/議題分類(triaging)
* _熟悉_ **Bash**/POSIX <ruby>shell 腳本<rp>(</rp><rt>shell script</rt><rp>)</rp></ruby>設計
* _熟悉_ **Ansible** 自動化技術以部署配置一致且有彈性的服務
* _熟悉_ **manpage** 與 **Texinfo** 軟體文件的閱讀能力
* _熟悉_ 下列用於建置軟體開發、測試與執行時期環境的**虛擬化技術解決方案**：
    + Docker/Docker Compose
    + LXD/LXC
    + Vagrant
    + VirtualBox
* _熟悉_ **Snap 軟體打包**，[Snap 為跨 Linux 散布版的軟體散佈解決方案](https://snapcraft.io)
* _具備_ 下列 **雲服務平台**的資源管理經驗：

    + 阿里雲
    + Amazon Web Services(AWS)
    + Cloudflare
    + 中華電信 hicloud
    + Google Cloud Platform(GCP)
    + 騰訊雲

  主要集中於下列的解決方案：

    + 內容傳遞網路(**CDN**)
    + 負載平衡(**LB**)
    + 類 **S3** 物件儲存系統
    + 虛擬機(**VM**)託管
    + 域名解析(**DNS**)

* _具備_ 下列**專案託管平台**的使用經驗：
    + GitHub
    + GitLab
    + Launchpad
* _具備_ 下列 **DevOps 架構**的建置經驗：
    + <ruby>持續整合(<b>CI</b>)<rp>(</rp><rt>Continuous Integration</rt><rp>)</rp></ruby>  
      用於專案內容的自動化品質管控
    + <ruby>持續交付(<b>CD</b>)<rp>(</rp><rt>Continuous Delivery</rt><rp>)</rp></ruby>  
      自動建構與交付可以立刻應用的產品
    + <ruby>服務部署自動化<rp>(</rp><rt>Deployment automation</rt><rp>)</rp></ruby>  
      透過即時通訊平台機器人實現服務的（半）自動化部署與回滾
* _具備_ 下列 **DevOps 產品**的使用經驗：
    + Drone CI
    + GitHub Actions
    + GitLab CI
    + Travis CI
* _具備_ 包含但不限於下列之**軟體建構系統**的使用與配置經驗：

    + GNU Autotools
    + CMake
    + Meson

  以建構符合客戶需求的產品
* _具備_ 對下列**程式語言** _基礎程度_ 之理解：

    + C
    + C++
    + Java
    + PHP
    + Ruby

  並可對程式進行小規模的修改以滿足客戶的需求
* _具備_ 對**物件導向程式設計(OOP)** _基礎程度_ 之理解
* _具備_ 使用 **PlantUML** 繪製<ruby>組件圖<rp>(</rp><rt>component diagram</rt><rp>)</rp></ruby>的經驗：
* _具備_ **軟體在地化(L10N)**與基於 GNU Gettext 程式庫之**軟體國際化(I18N)解決方案**使用經驗

### 語言能力

* 漢語（原生語言）
* 英語
    + 讀寫：熟練
    + 口說：中等

## 工作經歷

### 維運工程師<br><small>中信安科技<br>2019~2023</small>

* 負責開通、部署與監控客戶服務，並同時撰寫文件以維護專案的永續性
* 開發輔助下列領域的解決方案：
    + 產品建構、品質控管、交付之自動化(Drone CI/GitLab CI)
    + 服務與配置的自動化部署(Ansible/Bash)
    + 包含但不限於下列項目之主機、服務、資源的自動化監控(Ansible/Bash/Dig/OpenSSL/Python/ZABBIX)：
        - 域名效期監控
        - 檔案異動監控
        - 服務/主機可用性監控(HTTP/TCP/ICMP/IMAP)
        - 惡意<ruby>進程<rp>(</rp><rt>process</rt><rp>)</rp></ruby>監控
        - 服務可用性監控（包含根據客戶業務邏輯客製的實作）
        - TLS/SSL 證書效期監控
    + 資料備份與冗餘作業(Cron/Tar/Rsync)
    + 資訊安全防護（入侵偵測）
* 執行各種資訊安全事件的調查並提供相關意見
* 執行同儕工作結果的程式碼審閱以確保其在安全、品質與強固性上無虞
* 執行陌生技術的前期研究，包含但不限於：
    + 人工智慧技術（[百度人臉識別解決方案](https://cloud.baidu.com/doc/FACE/index.html)）
    + 專案依賴組件漏洞偵測（[OWASP Dependency-Check](https://owasp.org/www-project-dependency-check/)）
* 實作/維護包含但不限於下列公司的核心基礎建設：
    + 專案管理、程式碼託管、持續整合(CI)與交付(CD)(GitLab)
    + 遠端存取(WireGuard VPN/OpenVPN)
    + 檔案共享(WebDAV/Samba)
    + 內部網路(DHCP/DNS/Wireless)
    + 用於創建測試與生產環境的虛擬化服務(Proxmox VE)
* 輔助包含但不限於下列之行政事務：
    + 新進同仁的教育訓練
    + 工程部應徵人員的面試

## 個人作品

本人目前積極參與下列專案的貢獻：

* [Git Cola](http://git-cola.github.io): The highly caffeinated Git GUI  
  <https://github.com/git-cola/git-cola/commits?author=brlin-tw>
* [WoeUSB](https://github.com/slacka/WoeUSB): A tool that enables you to create your own windows installer USB key from an existing installation image  
  <https://github.com/slacka/WoeUSB/commits?author=brlin-tw>
* [The Snapcrafters](https://forum.snapcraft.io/t/join-snapcrafters/1325): A group of community contributors working to get snaps published by upstream projects  
  <https://forum.snapcraft.io/u/Lin-Buo-Ren/activity>

本人的大多數其他作品皆託管於 [GitHub](http://github.com) 與 [GitLab](https://gitlab.com)：  
<https://github.com/brlin-tw?tab=repositories&type=source>  
<https://gitlab.com/users/brlin/projects>

<!--
## 未來期望

本人希望未來能夠在下列領域中習得更多技能：

* DevOps(including but not limited to CI/CD and any kind of automation technologies)
* Embedded system development
* Linux kernel development(including but not limited to, driver development)

以及任何基於自由軟體的技術。
-->
