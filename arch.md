# 安裝說明

  * [基礎系統](/arch-basic-install)
  * [圖形系統](/arch-gui-install)
  * [聲音系統](/arch-sound)
  * [網路](/arch-network)

# pacman 快速操作

安裝軟體

    pacman -S [軟體名 或 軟體群組名]
    
移除軟體

    pacman -R [軟體名 或 軟體群組名]
    
搜尋軟體

    pacman -Ss [關鍵字]
    
搜尋**已安裝**軟體

    pacman -Qs [關鍵字]
    
查詢軟體資訊

    pacman -Si [軟體名]
    
查詢**已安裝**軟體資訊

    pacman -Qi [軟體名]
    
列出群組內的所有軟體名

    pacman -Sg [軟體群組名]
    
列出群組內**已安裝**的所有軟體名

    pacman -Qg [軟體群組名]
    
列出指定repo內所擁有的軟體

    pacman -Sl [repo名]
    
列出軟體所擁有的所有檔案

    pacman -Ql [軟體名]

查詢指定檔案所屬的軟體名

    pacman -Qo [完整檔案路徑 或 關鍵字]
    
## [pacman 操作手冊](/arch-pacman)

# [常用軟體](/arch-applications)

# AUR的使用
## AUR介紹
## 編譯、安裝AUR上的軟體
  1. 下載tarball
  2. 解壓縮tarball
  3. 編譯、包裝
  4. 安裝

## AUR前端軟體
  * yaourt

# 進階議題(也許可以共用的部份)
  * 如何檢查裝置是否被驅動
  * 

# Arch 專題
  * 打包自己的軟體
  * 控制makepkg編譯參數
  * 建立自己的repo
  * 把軟體還原成軟體包
  * *-dkms包的使用
  * 使用非官方repo
  * 在archlinux上使用LVM
  * 在archlinux上使用RAID
  * 架設LAMP
  * 

