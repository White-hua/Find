## 目录

* * *

- [目录](#目录)
- [渗透测试](#渗透测试)
  - [信息收集](#信息收集)
  - [漏洞扫描](#漏洞扫描)
  - [模糊测试](#模糊测试)
  - [在线工具](#在线工具)
  - [爆破攻击](#爆破攻击)
  - [流量控制](#流量控制)
  - [漏洞利用](#漏洞利用)
- [免杀](#免杀)
  - [webshell免杀](#webshell免杀)
  - [shellcode免杀](#shellcode免杀)
  - [防溯源](#防溯源)
- [后渗透](#后渗透)
  - [权限管理](#权限管理)
  - [权限提升](#权限提升)
  - [内网穿透](#内网穿透)
  - [内网横向](#内网横向)
  - [密码提取](#密码提取)
- [逆向工程](#逆向工程)
  - [安卓逆向](#安卓逆向)
  - [WINPE逆向](#winpe逆向)
- [代码审计](#代码审计)
- [工具类](#工具类)
- [插件类](#插件类)
- [社工钓鱼](#社工钓鱼)
- [框架项目](#框架项目)
- [学习文档](#学习文档)
- [各年护网exp整理](#各年护网exp整理)

* * *

## 渗透测试

* * *

### 信息收集

- 邮箱收集 ：https://hunter.io/

* * *

### 漏洞扫描

- fscan ：https://github.com/shadow1ng/fscan
- kscan ：https://github.com/lcvvvv/kscan
- afrog ：https://github.com/zan8in/afrog
- mscan(域) ：https://github.com/ddostest123/mscan
- 备份文件扫描 ：https://github.com/VMsec/ihoneyBakFileScan_Modify
- 信息泄露扫描 ：https://github.com/lijiejie/BBScan
- 扫描箱子 ：https://github.com/We5ter/Scanners-Box
- wifi/蓝牙测试 ：https://github.com/D3Ext/WEF

* * *

### 模糊测试

- URLFInder ：https://github.com/pingc0y/URLFinder
- ffuf ：https://github.com/ffuf/ffuf
- JSFinder ：https://github.com/Threezh1/JSFinder
- Packer-Fuzzer ：https://github.com/rtcatc/Packer-Fuzzer

* * *

### 在线工具

- 文件下载命令生成 ：https://forum.ywhack.com/bountytips.php?download
- 子域名爆破 ：http://z.zcjun.com/
- ip转数字 ：https://www.bejson.com/convert/ip2int/

* * *

### 爆破攻击

- raligun ：https://github.com/lz520520/railgun
- 字典 ：https://github.com/shadowabi/S-BlastingDictionary
- blasting(调用js) ：https://github.com/gubeihc/blasting

* * *

### 流量控制

- yakit ：https://github.com/yaklang/yakit
- hetty(老外写的好像类似burp的工具 没用过) ：https://github.com/dstotijn/hetty

* * *

### 漏洞利用

- CMS/OA漏洞利用
    - Apt-t00ls : https://github.com/White-hua/Apt_t00ls
    - 若依后台rce利用 ：https://github.com/lz2y/yaml-payload-for-ruoyi
    - 若依后台一键利用 ：https://github.com/thelostworldFree/Ruoyi-All
    - OA-EXPTOOL ：https://github.com/LittleBear4/OA-EXPTOOL
    - Exp-t00ls ：https://github.com/cseroad/Exp-Tools
    - Fvuln(批量) ：https://github.com/d3ckx1/Fvuln
    - 用友 ：https://github.com/wgpsec/YongYouNcTool
    - Tentacle ：https://github.com/orleven/Tentacle/
- 信息泄漏利用
    - swagger-exp ：https://github.com/lijiejie/swagger-exp
- 综合漏洞利用
    - 各种exp ：https://github.com/helloexp/0day
    - Awesome-POC ：https://github.com/Threekiii/Awesome-POC
    - nucli-exp全网整理 ：https://github.com/ExpLangcn/NucleiTP
- 中间件/组件 漏洞利用
    - shiro ：https://github.com/SummerSec/ShiroAttack2
    - solr ：https://github.com/Imanfeng/Apache-Solr-RCE
    - weblogic ：https://github.com/0xn0ne/weblogicScanner
    - weblogic(最新)：https://github.com/KimJun1010/WeblogicTool
    - JNDIExploit ：https://github.com/WhiteHSBG/JNDIExploit
    - ysoserial ：https://github.com/su18/ysoserial
    - jboss ：https://github.com/joaomatosf/jexboss
    - fastjson ：https://github.com/a1phaboy/FastjsonScan
- 主机漏洞利用
    - ms17-010 ：https://github.com/weizn11/MS17010_AllInOne
    - python_ms17-010原生 ：https://github.com/worawit/MS17-010
- 云上利用
    - 阿里云 ：https://github.com/iiiusky/alicloud-tools
- 软件漏洞利用
    - 向日葵rce ：https://github.com/Mr-xn/sunlogin_rce
- 硬件漏洞利用
    - 摄像头漏扫 ：https://github.com/jorhelp/Ingram
- 恶意压缩文件生成 ：https://github.com/jwilk/traversal-archives
- 各类漏洞总结：https://github.com/Awrrays/FrameVul
- 反序列化：https://github.com/woodpecker-framework/ysoserial-for-woodpecker

* * *

## 免杀

* * *

### webshell免杀

- 各类免杀shell生成 ：https://github.com/cseroad/Webshell_Generate
- 冰蝎免杀shell生成 ：https://github.com/Tas9er/ByPassBehinder
- 哥斯拉免杀shell生成 : https://github.com/Tas9er/ByPassGodzilla
- php异或免杀 ：https://github.com/splitline/PHPFuck
- php多种加密面杀 ：https://github.com/Z0fhack/AvoidkillingPHP
- Jsp白魔法 ：https://github.com/turn1tup/JspEncounter
- 动态在线免杀 ：https://github.com/StarsApt/webshell_bypass
- 内存马生成器 : https://github.com/hosch3n/msmap
- 精简webshell管理(有免杀效果) : https://github.com/b1ackc4t/Assassin
- disable_functions_bypass ：https://github.com/l3m0n/Bypass_Disable_functions_Shell
- 几年前的一个webshell免杀项目 ：https://github.com/LandGrey/webshell-detect-bypass
- php免杀webshell ：https://github.com/BugFor-Pings/PHPwebshell/tree/main

* * *

### shellcode免杀

- 堆加密 : https://github.com/TheD1rkMtr/HeapCrypt
- go混淆编译 ：https://github.com/burrowers/garble
- go源码混淆 ：https://github.com/unixpickle/gobfuscate
- c++加载器 ：https://github.com/midisec/BypassAnti-Virus
- go封装的各种加密算法 : https://github.com/wumansgy/goEncrypt
- python+cpp免杀 ：https://github.com/9emin1/charlotte
- go_shellcode加载器 https://github.com/TideSec/GoBypassAV

* * *

### 防溯源

- 腾讯云函数 ：https://mp.weixin.qq.com/s?__biz=MzkxMzIwNTY1OA==&mid=2247493632&idx=1&sn=3f01e8d26207c72431c11d3606af4cad

* * *

## 后渗透

* * *

### 权限管理

- Viper ：https://github.com/FunnyWolf/Viper
- Cat_4.5 ：https://github.com/TryGOTry/CobaltStrike_Cat_4.5
- 远控上线方案 ：https://github.com/RuoJi6/Deskbypass

* * *

### 权限提升

- CDK(Docker逃逸) ：https://github.com/cdk-team/CDK
- postsql提权 ：https://github.com/No-Github/postgresql_udf_help
- 土豆家族 ：https://github.com/antonioCoco/JuicyPotatoNG
- godpotato ：https://github.com/BeichenDream/GodPotato
- linux提权 ：https://github.com/liamg/traitor
- PEASS-ng ：https://github.com/carlospolop/PEASS-ng

* * *

### 权限维持

- Linux权限维持 ：https://github.com/RuoJi6/HackerPermKeeper

* * *

### 内网穿透

- Stowaway ：https://github.com/ph4ntonn/Stowaway
- 毒刺 ：https://github.com/FunnyWolf/pystinger
- 密码爆破 ：https://github.com/Porchetta-Industries/CrackMapExec

* * *

### 内网横向

- SharpHostInfo(类似netspy深信服写的) ：https://github.com/shmilylty/SharpHostInfo
- wmiexec等协议横向 ：https://github.com/rootclay/WMIHACKER
- wmiexec ：https://github.com/XiaoliChan/wmiexec-Pro

* * *

### 密码提取

- HackBrowser ：https://github.com/moonD4rk/HackBrowserData
- Xshell密码提取导出 ：https://github.com/JDArmy/SharpXDecrypt
- ProcDump-linux ：https://github.com/Sysinternals/ProcDump-for-Linux

* * *

## 逆向工程

* * *

### 安卓逆向

- 安卓逆向 ：https://github.com/dqzg12300/MikRom
- AppInfoScanner ：https://github.com/kelvinBen/AppInfoScanner
- 微信小程序逆向 https://github.com/ezshine/wxapkg-convertor
- 国外的一个 ：https://github.com/MobSF/Mobile-Security-Framework-MobSF

* * *

### WINPE逆向

- x64dbg ：https://github.com/x64dbg/x64dbg

* * *

## 代码审计

- mysql数据库监控 ：https://github.com/fupinglee/MySQLMonitor
- chatgpt自动审计 : https://github.com/YulinSec/ChatGPTScan-SASTcd
- Codepy ：https://github.com/webraybtl/CodeQLpy

* * *

## 工具类

- win10虚拟机工具齐全 ：https://github.com/makoto56/penetration-suite-toolkit
- 环境自动部署工具 ：https://github.com/ffffffff0x/f8x
- 代理白嫖 ：https://github.com/ja9er/Gofreeproxy
- BerylEnigma(加解密) ：https://github.com/ffffffff0x/BerylEnigma
- android渗透盒子 ：https://github.com/H4ckBu7eer-EX/h4tools
- mac微信防撤回 ：https://github.com/sunnyyoung/WeChatTweak-macOS
- electerm ：https://github.com/electerm/electerm
- sql语句在线测试：https://www.db-fiddle.com/

* * *

## 插件类

- burp插件
    - fastjson ：https://github.com/pmiaowu/BurpFastJsonScan
- cs插件
    - OLa ：https://github.com/d3ckx1/OLa
- Google插件
    - Hack-Tools ：https://github.com/LasCC/Hack-Tools

* * *

## 社工钓鱼

- 钓鱼演练 ：https://github.com/xiecat/goblin
- 字典生成 ：https://github.com/G0mini/spark

* * *

## 框架项目

- ExpDemo-JavaFx ：https://github.com/yhy0/ExpDemo-JavaFX
- 武器库平台 ：https://github.com/Ascotbe/Medusa

* * *

## 学习文档

- 实战技巧
    - 渗透Tips ：https://github.com/Power7089/PenetrationTest-Tips
    - 渗透Tips2 ：https://github.com/ffffffff0x/Pentest101
    - 我是赏金猎人系列 ：https://github.com/J0o1ey/BountyHunterInChina
    - hackone漏洞报告 ：https://github.com/reddelexc/hackerone-reports
    - 安卓app渗透 ：https://github.com/WindXaa/Android-Vulnerability-Mining
    - f8x渗透tips ：https://github.com/ffffffff0x/Pentest101
    - 红队笔记 ：https://github.com/biggerduck/RedTeamNotes
- Java
    - spring boot相关漏洞学习资料，利用方法 ：https://github.com/LandGrey/SpringBootVulExploit
    - Java漏洞及代码学习 ：https://github.com/JoyChou93/java-sec-code
    - Jsp免杀 ：https://github.com/threedr3am/JSP-WebShells
    - fastjson ：https://mp.weixin.qq.com/s/F3zkjc_7iby4dsAQu2COdg
    - Java学习笔记(较全) ：https://github.com/Drun1baby/JavaSecurityLearning
- PHP
    - 代码审计练习 ：https://github.com/hongriSec/PHP-Audit-Labs
- Sql注入
    - sql注入技巧学习文档 ：https://github.com/kleiton0x00/Advanced-SQL-Injection-Cheatsheet
- 内网渗透
    - 域渗透 ：https://github.com/0range-x/Domain-penetration_one-stop
- 资料
    - fffffff0x团队安全知识框架 ：https://github.com/ffffffff0x/1earn
    - 资料表单 ：https://github.com/shmilylty/awesome-hacking
    - 很多书 ：https://github.com/olist213/Information_Security_Books
    - 各类资料(逆向较全) ：https://github.com/shmilylty/awesome-hacking
- 收集类项目
    - 优秀项目收集：https://github.com/guchangan1/All-Defense-Tool
    - 404星链 ：https://github.com/knownsec/404StarLink
    - 一些在线的工具 ：https://github.com/r0eXpeR/Online_Tools
    - 外国人的工具及学习总结 ：https://github.com/vitalysim/Awesome-Hacking-Resources
    - 精彩逆向文章！ : https://github.com/darbra/sperm
    - 免杀工具及文章收集项目 ：https://github.com/alphaSeclab/anti-av
    - readtool(红队资料工具) ：https://github.com/xiaoZ-hc/redtool
    - vulnerability-paper ：https://github.com/MrWQ/vulnerability-paper
- webshell免杀
    - php免杀文章 ：https://github.com/AabyssZG/WebShell-Bypass-Guide

* * *

## 各年护网exp整理

- 2021 ：https://github.com/Ershu1/2021_Hvv
- 2022 ：https://github.com/Phuong39/2022-HW-POC
- 2023 : https://github.com/wy876/POC/tree/main
