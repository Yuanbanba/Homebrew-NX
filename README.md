原版大气层增强整合包可精简组件说明（2022.12.26）

部分插件和软件没有更新了，所以加些fork分支

https://pan.baidu.com/s/1QSrewJO5pyRXDxEhmrx4Gw?pwd=nwsx

https://github.com/Yuanbanba/Atmosphere/releases

一、大气层和特斯拉插件

（1）特斯拉插件内核

https://github.com/WerWolv/nx-ovlloader/releases

https://github.com/WerWolv/Tesla-Menu/releases

https://github.com/zdm65477730/Tesla-Menu/releases

https://github.com/WerWolv/ovl-sysmodules/releases

https://github.com/zdm65477730/ovl-sysmodules/releases

删除文件夹1个

tf：atmosphere/contents/420000000007E51A

删除文件2个

tf：switch/.overlays/ovlmenu.ovl

tf：switch/.overlays/ovlsysmodules.ovl

如删除tesla内核，建议删除文件夹tf：switch/.overlays/

（2）Edizon金手指插件

https://github.com/WerWolv/EdiZon/releases

https://github.com/proferabg/EdiZon-Overlay/releases

删除文件1个

tf：switch/.overlays/ovledizon.ovl

ovledizon.ovl=阉割版金手指edizon.nro，只可以读取atmosphere/contents/xxxx/下的cheat代码。

但是免去游戏中切换去相册开启edizon.nro，如果只用金手指代码，可删除edizon.nro。

（3）mission control插件，支持蓝牙无线连接第三方手柄，需要deepsea工具箱后台开启，重启生效。

https://github.com/ndeadly/MissionControl/releases

删除文件夹3个

tf：atmosphere/contents/010000000000bd00/

tf：atmosphere/exefs_patches/bluetooth_patches/

tf：config/missioncontrol/

（4）sys-con插件，支持usb有线连接第三方手柄，需要deepsea工具箱后台开启，直接生效。

https://github.com/cathery/sys-con/releases

删除文件夹2个

tf：atmosphere/contents/690000000000000D/

tf：config/sys-con/

（5）ldn-mitm插件，破解机局域网联机插件，需要deepsea工具箱后台开启，重启生效。

https://github.com/spacemeowx2/ldn_mitm/releases

删除文件夹2个

tf：atmosphere/contents/4200000000000010/

tf：switch/ldnmitm_config/

删除文件1个

tf：switch/.overlays/ldnmitm_config.ovl

（6）SaltyNX插件，手持底座切换插件，需要deepsea工具箱后台开启，重启生效。

https://github.com/masagrator/SaltyNX/releases

https://github.com/masagrator/ReverseNX-Tool/releases

https://github.com/masagrator/ReverseNX-RT/releases

删除文件夹2个

tf：atmosphere/contents/0000000000534C56

tf：saltySD

删除文件2个

tf：switch/.overlays/ReverseNX-RT-ovl.ovl

tf：switch/ReverseNX-Tool.nro

（7）sys-clk插件，超频插件，需要deepsea工具箱后台开启，重启生效。

https://github.com/retronx-team/sys-clk/releases

删除文件夹2个

tf：atmosphere/contents/00FF0000636C6BFF

tf：config/sys-clk

删除文件2个

tf：switch/sys-clk-manager.nro

tf：switch/.overlays/sys-clk-overlay.ovl

（8）emuiibo插件，需要deepsea工具箱后台开启，重启生效。

https://github.com/XorTroll/emuiibo/releases

删除文件夹2个

tf：atmosphere/contents/0100000000000352/

tf：emuiibo/

删除文件1个

tf：switch/.overlays/emuiibo.ovl

（9）Edizon-SE和Breeze，金手指nro插件，带存档管理器功能

https://github.com/tomvita/EdiZon-SE/releases

删除文件夹5个

tf：atmosphere/contents/054e4f4558454000/

tf：atmosphere/contents/0100000000001013/

tf：atmosphere/contents/010000000000000D/

tf：switch/EdiZon/

tf：switch/breeze/

（10）Status-Monitor-Overlay.ovl状态监视插件

https://github.com/masagrator/Status-Monitor-Overlay/releases

删除文件1个

tf：switch/.overlays/Status-Monitor-Overlay.ovl

Status-Monitor-Overlay.ovl=NS状态监视工具。退出方法:同时按压左右摇杆，然后按B退出

（11）fastcfwswitch插件，快速切换引导，只能在注入机与补丁机上使用

https://github.com/Hartie95/fastCFWswitch/releases

删除文件夹1个

tf：config/fastCFWSwitch/

删除文件1个

tf：switch/.overlays/fastCFWswitch.ovl

（12）Triplayer插件，音乐播放器，音乐文件tf：music/

https://github.com/tallbl0nde/TriPlayer/releases

删除文件夹2个

tf：atmosphere/contents/4200000000000FFF/

tf：switch/triplayer/

删除文件1个

tf：switch/.overlays/ovl-TriPlayer.ovl

二、相册nro自制软件

位于tf：switch/下，除了tinfoil需要license文件夹，其余nro都只需一个XXX.nro文件

nro自制软件删与不删不影响系统稳定，根据自己需要增减。

（1）Switch_90DNS_tester.nro

https://github.com/meganukebmp/Switch_90DNS_tester/releases

90dns检测，联网屏蔽switch服务器

（2）aio-switch-updater.nro

https://github.com/HamletDuFromage/aio-switch-updater/releases

联网下载各种补丁、金手指，适合被ban机器联网，未ban的机器不建议联网

（3）AtmoXL-Titel-Installer.nro

https://github.com/dezem/AtmoXL-Titel-Installer/releases

https://github.com/Huntereb/Awoo-Installer/releases

（Awoo停止更新）

https://github.com/lsp199308/Awoo-Installer/releases

（Awoo停止更新）

代替Awoo游戏安装器，通吃xci/nsp/nsz，支持新出的格式

（4）Firmware-Dumper.nro

https://github.com/mrdude2478/Switch-Firmware-Dumper/releases

提取离线升级固件，按Daybreak要求命名

（5）Calculator_NX.nro

https://github.com/EmreTech/Calculator_NX/releases

实用计算器

（6）checkpoint.nro

https://github.com/FlagBrew/Checkpoint/releases

存档管理器，建议平时养成经常备份存档的习惯

（7）dbi.nro

https://github.com/rashevskyv/dbi/releases

是新出的多功能软件，集成nxmtp，突破4g文件传输限制，usb安装等多种功能，体积小巧

（8）deepsea-toolbox.nro

https://github.com/Team-Neptune/DeepSea-Toolbox/releases

https://github.com/WerWolv/Hekate-Toolbox/releases

深海工具箱，可以管理后台插件，免注入重启等功能

更换为Hekate-Toolbox.nro，界面一样，最新版支持续航/Lite/OLED关机重启

（9）ftpd.nro

https://github.com/mtheall/ftpd/releases

FTP工具NS端，支持电脑FTP软件

（10）goldleaf.nro


https://github.com/XorTroll/Goldleaf/releases

金叶子文件管理器/nsp安装器，功能较多，可以离线删除帐号等

（11）haku33.nro

https://github.com/StarDustCFW/Haku33/releases

清空破解信息，初始化洗白

（12）appstore.nro

https://github.com/fortheusers/hb-appstore/releases

自制软件商店，同上，也是需要联网

（13）jksv.nro

https://github.com/J-D-K/JKSV/releases

ns存档管理器，可以支持动森等游戏存档，功能较checkpoint多一些

（14）linkalho.nro

https://github.com/rdmrocha/linkalho/releases

离线绑任天堂账号

（15）N-Xplorer.nro

https://github.com/CompSciOrBust/N-Xplorer/releases

带文本编辑功能的文件管理器

（16）NX-Activity-Log.nro

https://github.com/tallbl0nde/NX-Activity-Log/releases

游戏时间统计工具

（17）nx-shell.nro

https://github.com/joel16/NX-Shell/releases

文件管理器，加载速度快，支持复选框，不需要也可以删除

（18）nxdumptool.nro

https://github.com/DarkMatterCore/nxdumptool/releases

可以提取卡带与数字版游戏为xci/nsp格式，支持本体、补丁和dlc的提取

（19）NXThemesInstaller.nro

https://github.com/exelix11/SwitchThemeInjector/releases

自制主题安装器

（20）Payload_Launcher.nro

https://github.com/suchmememanyskill/Payload_Launcher/releases

payload加载器

（21）pplay.nro

https://github.com/Cpasjuste/pplay/releases

视频播放器，视频文件名称不支持中文

（22）Safe_Reboot_Shutdown.nro

https://github.com/dezem/Safe_Reboot_Shutdown/releases

一键关机重启，L关机R重启，兼容Mariko

（23）switchtime.nro

https://github.com/3096/switch-time/releases

校对时间，绕过90dns与隐藏序号

（24）Tencent-switcher-GUI.nro

https://github.com/CaiMiao/Tencent-switcher-GUI/releases

国行系统转外服切换，联网会ban机

（25）tinfoil.nro

http://tinfoil.io/Download#download

锡纸是集成文件管理器/安装器的强大软件

（26）tinwoo.nro

https://github.com/mrdude2478/TinWoo/releases

https://github.com/blawar/tinleaf/releases

（Tinleaf停止更新）

游戏安装器，支持外接U盘/移动硬盘安装nsp/xci

（27）wiliwili.nro

https://github.com/xfangfang/wiliwili/releases

哔哩哔哩视频，前端hbmenu进入，和Checkpoint一样。

三、其它可以精简的内容

（1）如果是非tx pro软破机或者sx core/lite硬破机用户，根目录的boot.dat（sx gear1.1）和payload.bin（hekate）两个文件可以删除。

（2）sxgear1.1/boot.dat和sxos3.1/boot.dat，用于切换sx gear与sxos的引导，可以删除。

（3）hbmenu.nsp是万能前端hbmenu，安装完毕可以删除。

（4）sxos3.1/titles/00FF0012656180FF是AutoLoader1.4，SXOS免相册加载工具，要复制到sxos/titles/。

（5）choidujournxv102.nro是在sxos下使用的系统升级工具，要复制到switch/。

（6）bootloader/payloads/是Hekate二次引导文件，除fusee.bin是大气层引导，其它都可删

lockpick_rcm.bin

https://github.com/shchmue/Lockpick_RCM/releases

https://github.com/dezem/Lockpick_RCM/releases

tegraexplorer.bin

https://github.com/suchmememanyskill/TegraExplorer/releases

https://github.com/dezem/TegraExplorer/releases

CommonProblemResolver.bin

https://github.com/Team-Neptune/CommonProblemResolver/releases
