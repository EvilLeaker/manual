comments: true
# 
<figure markdown>
<div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/common/chusan_logo.png"> </div>
<div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/common/cabinet_1.png"/> </div>
</figure>

!!! info "本页可发表评论，如有问题、反馈、评价等，欢迎发表评论"

!!! danger "重要提醒"

    首先请仔细阅读教程的每一个字，出现问题请确认你是否认真详细阅读了教程的每一步。

    出现问题之后请阅读另外一篇常见问题尝试解决其中你遇到的问题。

    如果你的问题在常见问题之外，再在群以及社区中寻求帮助！

    提问的时候请一同发布你的游戏界面，Log或设置截图以及文字详细描述你出现的问题，只扔个图问这是怎么回事这种问题是无法帮你解答的！！

<div class="grid cards" markdown>

-   :fontawesome-solid-wrench:{ .lg .middle } __游戏版本__

    ---

    CHUNITHM VERSE

    Version 2.30.00

    ---

    **[:octicons-arrow-right-24: 获取HDD](https://dc.evilleaker.com/)**

-   :fontawesome-solid-file-circle-plus:{ .lg .middle } __Option数据包__

    ---

    A001~A191(Verse Final)

-   :fontawesome-solid-server:{ .lg .middle } __网络服务__

    ---

    rin Net

    ---

    **[:octicons-arrow-right-24: 前往rin Net](https://portal.naominet.live/)**

-   :fontawesome-solid-clock:{ .lg .middle } __最后更新__

    ---

    2025/07/16 (Tue)

</div>

---

## 游玩前的准备

!!! danger "注意事项"

    如果您已在PC上游玩过CHUNITHM并且配置好了HDD，仅更换了手台，请参阅 **[配置控制器io](#io)** 部分

    如果您从未在PC上游玩过HDD，请继续往下阅读教程。

!!! warning "游戏不可放置在**`E:\`**与**`Y:\`**，请将游戏文件放置在其他硬盘分区"

!!! tip ""

    下载如下文件

    <img width="700" src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0000.png">

### 安装Runtime (Windows运行时安装包)

!!! tip ""

    下载  **Runtime** 

    [:octicons-arrow-down-24: Download Runtime](https://hitiko-my.sharepoint.com/:u:/p/evilleaker/EffD9kk4fiFEnJVcOrSgVI0B3gOx86gw9WBRLqdUIxvvjg){ .md-button .md-button--primary target="_blank"}

    解压后获得如下文件

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0001.png"/> </div>

    运行**`DirectX.bat`**并按照窗口提示完成安装

    运行**`VC.bat`**并按照窗口提示完成安装

### 提取游戏文件

!!! warning "HDD路径不要有：空格、中文、任何特殊符号等，请尽量使用半角英数字。"

??? note "使用Windows挂载虚拟磁盘方式提取HDD"

    鼠标左键双击**`SDHD_2.30.00_20241112124752_0.vhd`**

    Windows会挂载一个新的硬盘分区(具体盘符根据每个人情况不同而不同)

    进入这个磁盘分区，将其中的所有文件复制出来（例如：**`C:\SDHD\`**）

    提取完文件后可以关闭磁盘分区窗口，并在这个分区上点击鼠标右键选择**`弹出(Eject)`**卸载磁盘分区

    你也可以挂载虚拟磁盘后直接在其中运行HDD，配置方法与提取出来并无区别

??? note "使用7-Zip提取HDD"

    下载 **7-Zip**

    [:octicons-arrow-down-24: Download 7-Zip](https://oss.am-all.com.cn/download/files/7-Zip.rar){ .md-button .md-button--primary }

    解压并安装 **7-Zip**

    解压 **`ExFat7z.rar`**，在7-Zip安装目录中新建一个**`Formats`**文件夹，将解压的两个dll文件复制进去

    配置好7-Zip后在**`SDHD_2.30.00_20241112124752_0.vhd`**上点击鼠标右键，选择**`打开方式→7zip文件管理器`**或**`点击右键→7zip→打开压缩包`**，如下图：

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0002.png"> </div>

    提取后获得如下文件：

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0003.png"> </div>

### 安装已解密的文件

!!! tip ""

    将 **`chusanApp.exe`** 与 **`amdaemon.exe`** 放入HDD中的 **`bin`** 文件夹中并覆盖源文件

    !!! note "注意事项"
    
        上述**`chusanApp.exe`**已打过可正常游玩所需的补丁
    
        如有其他修改补丁的需求，请访问  **[DATA CENTER - 补丁工具页(侧边栏进入)](https://dc.evilleaker.com/)**
    
        - 打过补丁的 **`chusanApp.exe`** 在保存时有可能会被误报为病毒，这是正常现象，请给exe文件添加到杀毒软件白名单
    
        - 补丁站仅支持本教程提供之 **`chusanApp.exe`** 的修改！

### 安装option

!!! tip ""

    下载并解压 **option(A001~A162).zip**

    将 **`option`** 文件夹复制到HDD文件夹下的 **`bin`** 文件夹中

    - CHUNITHM官方option文件夹都以**`Axxx`**命名,**`x`**均为数字，如果你在其他地方下载到非下图所示的option文件夹则可能为玩家自制内容

    - 正确的option路径应为**`bin\option`**，option文件夹中的内容应为下图所示：

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0004.png"> </div>

    - 如option路径为**`bin\option\option`**这样嵌套，则游戏不能正确读取option数据

    ??? warning "关于官方option的命名规则"

        CHUNITHM 以半年为一个小版本更新，一年一次大版本更新，例如：LUMINOUS / LUMINOUS PLUS

        官方option数据命名也以此作为区分：

        - A001 - 现行版本以A001作为游戏发布的首日(Day-1)更新

        - A071 - 现行版本以前两位作为更新月份，最后一位则为这个月份的第几个更新包，如最后一位是**`0`**，则固定为待机广告视频更新包

### 安装官方删除曲补充包

!!! tip ""

    - 下载并解压 **A300_omni_250309.zip**

    - 将 **`A300`** 文件夹复制到HDD文件夹下的 **`bin\option`** 文件夹中

    - 如option路径为 **`bin\option\A300\A300`** 这样嵌套，则游戏不能正确读取option数据

    !!! warning "注意事项"

        - 本补充包包含了从旧框初代无印开始到Luminous Plus为止的所有官方 **已删除歌曲及相关配套的资源** ，以及 **已删除 ULTIMA / World's End 谱面** ，并且删除曲部分已重新排序，非常老旧的歌曲会安排在每个分类的最末尾并按照ID编号从小到大排列，比较新的删除曲则按照删除前的官方排序。

        - 本补充包并不包含 **已删除歌曲及相关配套的资源、删除谱面** 以外的任何已被官方在新版本删除的内容，比如联动地图，过往的已删除地图已累计达到200左右，全部安装会导致游戏卡顿，不建议使用，如需解锁相关角色请到rin Net网页后台相关功能中操作！

### 安装segatools

???+ note "fufubot segatools v1.0.3.5 更新内容"

    修复内容：

	- 修复COM4口有东西导致读卡器模拟自动关闭的问题 现在将enable改为2或者不写时为才会检测COM口上有没有东西决定是否开关读卡器模拟

	- 修复大四一直刷卡的问题

    新增功能：

    - 增加源3支持

!!! tip ""

    下载 **fufubot segatools** 并解压至任意文件夹

    [:octicons-arrow-down-24: Download fufubot segatools](https://oss.am-all.com.cn/download/files/chusan_segatools_1_0_3_5_by_fufubot_team_release_by_evil_chinese.zip){ .md-button .md-button--primary target="_blank"}

    解压后获得如下文件：

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0005.png" width = 600/> </div>

    将上述文件全部复制到HDD中的 **`bin`** 文件夹下即可完成安装

### 安装ICF

!!! tip ""

    解压 **ICF_2.30.zip**

    将 **`ICF1`** 与 **`ICF2`** 两个文件放置于 **`bin\amfs`** 文件夹内

---

## 配置segatools

!!! tip ""

    由于segatools没有图形配置工具，因此您必须手动修改 **segatools.ini** 来进行配置，配置文件位于**`bin`**文件夹中

    *[segatools.ini]:如果找不到此文件，请先看上面安装segatools章节

    建议您使用支持语法高亮的文本编辑器（例如：Notepad++、VS Code、Sublime Text）来修改配置文件

    !!! danger "注意事项"

        请不要使用富文本编辑器（例如：Word、WPS、写字板）来修改配置文件，可能会让配置文件格式错误而导致游戏读取配置文件出错

### `[vfs]`

!!! tip ""

    如果您已按照上面 **[安装ICF](#icf)** 步骤配置对应文件夹，请将对应文件夹的路径填写到**`[vfs]`**对应的选项中

    - 最新版 **`fufubot team版segatools`** 已修复 **`vfs`** 路径文件，无需配置到根目录了

    - 安装好 **`segatools`** 后 **`vfs`** 路径保持默认即可

    ```ini
    [vfs]
    amfs=amfs
    option=option
    appdata=appdata
    ```

### `[gpio]`

!!! tip ""

    !!! warning "注意事项"

        外网最新版segatools中**`[gpio]`**已重新命名为**`[system]`**，本文中以**`fufubot team`**版为准

    - 如果不进行本地局域网联机相关，请勿修改**`dipsw1`**，保持默认**`1`**

        * 局域网中仅有1台运行HDD的主机，**`dipsw1`**请设置为**`1`**

        * 局域网中有复数台运行HDD的主机(2-4台)，标准机设置为**`1`**(仅1台)，其余从机设置为**`0`**

    - 如果您的显示器刷新率 ≥120Hz，请将**`dipsw2`**与**`dipsw3`**设置为**`0`**：

    ```ini
    [gpio]
    dipsw1=1
    dipsw2=0
    dipsw3=0
    ```

    - 如果您的显示器刷新率为60Hz，请将**`dipsw2`**与**`dipsw3`**设置为**`1`**：

    ```ini
    [gpio]
    dipsw1=1
    dipsw2=1
    dipsw3=1
    ```

    !!! danger "请严格按照上述要求修改dipsw设置，错误的设置可能会让游戏无法正常启动！"

### `[gfx]`

!!! tip ""

    - 如需全屏运行游戏请将**`windowed`**修改为**`0`**

    ```ini
    [gfx]
    windowed=0
    framed=1
    monitor=0
    ```

    - 如需窗口运行游戏请将**`windowed`**修改为**`1`**

    ```ini
    [gfx]
    windowed=1
    framed=1
    monitor=0
    ```

    - 无边框窗口请将**`framed`**修改为**`0`**

    - 有边框窗口请将**`framed`**修改为**`1`**

    !!! warning "注意事项"
    
        CHUNITHM以固定的1920x1080分辨率渲染游戏，不可更改
    
        如果你的显示器分辨率大于1080P并且需要全屏窗口运行游戏，请将系统分辨率降低到1080P或使用全屏进行游戏
    
        不管以何种方式运行游戏，**`monitor=0`** 都无需修改，请保持默认设置

### `[aime] / [aimeio]`

!!! tip ""

    如果你使用官方读卡器或支持官方协议的第三方读卡器，请将**`enable`**修改为**`0`**并正确配置读卡器端口号

    ```ini
    [aime]
    enable=0
    ```

    如果你没有任何读卡器设备，请将**`enable`**修改为**`1`**以启动segatools模拟读卡器，Yubideck(大四台)修改为**`1`**

    ```ini
    [aime]
    enable=1
    ```

    Yubideck(大四台)需要另外设置**`[aimeio]`**以启动手台上的读卡器,请将**`;path=aimeio_yubideck.dll`**前的分号**`;`**删除

    ```ini
    [aimeio]
    path=aimeio_yubideck.dll
    ```

    使用拥有自己专有io的第三方读卡器，需要将**`;path=aimeio.dll`**前的分号**`;`**删除，此处文件名请以读卡器作者提供的为准

    ```ini
    [aimeio]
    path=aimeio.dll
    ```

### `[io3]`

!!! tip ""

    io3中的选项负责映射**`TEST`**、**`SERVICE`**、**`COIN`**三个机台功能按键，默认为键盘字母上面的数字**`1`**、**`2`**、**`3`**

    如需修改按键键值请参考下面链接

    - **[16进制标准键盘码值表](https://blog.csdn.net/gao5528/article/details/5991495)**

---

## 配置控制器io

!!! tip ""

    本文仅展示**`TASOLLER`**、**`TASOLLER PLUS`**、**`Yubideck`**的io配置方法，手台控制器的连接方法请查看左侧导航栏**`控制器`**部分

    - 本章节依旧需要在**`segatools.ini`**中进行配置

### TASOLLER / TASOLLER PLUS

<div class="grid cards" markdown>

-   :fontawesome-solid-question:{ .lg .middle } __我使用TASOLLER，且第一次游玩__

    ---

    请先阅读手台教程并续按教程配置

    [:octicons-arrow-right-24: 查看**TASOLLER 控制器说明**](https://performai.evilleaker.com/manual/controller/chuni/tasoller/)

-   :fontawesome-solid-question:{ .lg .middle } __我使用TASOLLER +，且第一次游玩__

    ---

    请先阅读手台教程并续按教程配置

    [:octicons-arrow-right-24: 查看**TASOLLER PLUS 控制器说明**](https://performai.evilleaker.com/manual/controller/chuni/tasollerplus/)

-   :fontawesome-solid-question:{ .lg .middle } __我从TASOLLER或其他设备更换到PLUS，已有玩过并已配置好HDD__

    ---

    下载 **[TASOLLER PLUS io](https://oss.am-all.com.cn/download/files/tasoller_plus.dll)**

    按照下方配置 **`TASOLLER PLUS io`** 即可游玩

-   :fontawesome-solid-question:{ .lg .middle } __其他问题__

    ---

</div>

!!! tip ""

    请在 **`[chuniio]`** 部分中将默认的 **`chuniio-mux.dll`** 注释掉，并按照下方设置在 **`path=chuniio-mux.dll`** 前加上分号 **`;`**

    ```ini
    [chuniio]
    ;path=chuniio-mux.dll
    ```

    - 使用 **TASOLLER** 请删除 **`;path=tasoller.dll`** 前的分号 **`;`** 取消注释状态

    ```ini
    [chuniio]
    path=tasoller.dll
    ```

    - 使用 **TASOLLER PLUS** 请删除 **`;path=tasoller_plus.dll`** 前的分号 **`;`** 取消注释状态

    ```ini
    [chuniio]
    path=tasoller_plus.dll
    ```

### Yubideck (大四控制器/舟台)

!!! tip ""

    请在**`[chuniio]`**选项中将默认的**`chuniio-mux.dll`**注释掉，按照下方设置在**`path=chuniio-mux.dll`**前加上分号**`;`**

    ```ini
    [chuniio]
    ;path=chuniio-mux.dll
    ```

    - 使用Yubideck(大四台)请删除**`;path=yubideck.dll`**前的分号**`;`**取消注释状态

    ```ini
    [chuniio]
    path=yubideck.dll
    ```

    **`[zhousensor]`** 为 **`Yubideck(大四台)`** 专用设置，默认即可，如需设置请按照 **`segatools.ini`** 中的说明进行设置

    ```ini
    [zhousensor]
    ; YubiDeck Need this
    ; You can set YubiDesk side light color here, the value is RGB, range is 0-255
    ;side_red=0
    ;side_green=255
    ;side_blue=0

    ;side_random=1
    
    ; You can set this to 1 to use real Aime Card ID for old Aime card 
    ; This function only works for YubiDeck(DASI)'s Aime Card Reader
    real_aime=1
    
    ; You can set this to 1 to let game control LED side light
    ; This option is mutually exclusive with the above rgb option
    ; 0 = not control 1 = control
    real_led=1
    
    ; Set this to 0 will disable any led output from game
    ;led_output=0
    ```

---

## 连接网络

!!! note "注意事项"

    游戏大部分功能需要连接到网络服务器才可以正常使用以及登录用户，离线状态下仅可使用访客游玩游戏。

    游戏服务器分为**`在线服`**与**`离线服`**，请按自身情况选择对应服务器使用。

!!! tip "在线服务器 (Rin Net)"

    打开**`segatools.ini`**，在**`[dns]`**选项中设置**`default`**为您需要连接的服务器地址。

    - 请不要将**`http://`**与**`https://`**添加到服务器地址中

    - 请不要将**`127.0.0.1`**或**`localhost`**作为服务器地址

    Rin Net dns：**aqua.naominet.live**

    服务器前端：https://portal.naominet.live/login

    ```ini
    [dns]
    default=aqua.naominet.live
    ```

    连接Rin Net需要申请Keychip才可正常联网，如何注册请查看下面的文章。

    注册完**`Keychip`**后需要填写到**`[keychip]`**选项中

    ```ini
    [keychip]
    id=AXXE-XXXXXXXXXXX
    ```

    - **`Keychip(狗号)`**均以**`AXXE-XXXXXXXXXXX`**格式填写，**`X`**为英数字

    ??? warning "如何申请Rin Net Keychip"
    
        如何配置？
    
        我自己玩：
    
        - 前往[**机台页**](https://portal.naominet.live/keychip)，点击“**创建机台**”。
    
        - 按[**机台页**](https://portal.naominet.live/keychip)中“**如何使用机台序列号**”一栏中的提示编辑**segatools.ini**。
    
        我用朋友的机器玩：
    
        - 让你的朋友按照本文“**我自己玩**”部分操作。
    
        - 在[**机台页**](https://portal.naominet.live/keychip)中“**受信任的机台**”下点击“**添加信任**”，输入朋友刚才创建的**机台序列号**后点击确定
    
        我在窝/机厅玩：
    
        - 什么都不用做
    
        我是开窝/开机厅/写查分bot的：
    
        - 按照本文“**我自己玩**”部分操作。
    
        - [**填写问卷**](https://wj.qq.com/s2/14399591/ca04/)以申请白名单
    
        其它事项：
    
        - 不配置KeychipID将在2024/5/1后无法登录游戏
        
        - 如果有其他问题可以加入QQ群: [**295954906**](https://qm.qq.com/q/q81C7iA2Aw)

!!! tip "离线服务器 (ARTEMiS与AquaDX)"

    离线服务器都需要进行比较复杂的设置，详情请参阅**[ARTEMiS](https://gitea.tendokyu.moe/Hay1tsme/artemis/src/branch/develop/docs/INSTALL_WINDOWS.md)**与**[AquaDX](https://github.com/hykilpikonna/AquaDX?tab=readme-ov-file#usage-v1-developmental-preview)**的官方指南来配置本地服务器。

### 全国对战

!!! abstract "Rin NET目前已支持全国对战"

    !!! note "已支持VERSE，请下载并更新最新版本 **duolinguo.dll**"

    在此模式中可以随机匹配2~4位玩家进行即时对战或进行VS CPU的人机对战(不支持1 VS 3CPU)

    如何连接全国对战，请参阅 **[全国对战](national_battle.md)**

---

## HDD运行与设置

!!! tip "根据上面的步骤，现在你已经具备运行HDD的基本环境了，下面将进行一些运行前的最后设置"

### 修复 OpenSSL

!!! tip ""

    如果您的CPU是Intel Core 10th Gen或以上版本，请右键单击 **`bin\start.bat`** 选择 **`编辑`**，将下面高亮处代码添加至文件开头并保存

    ```batch hl_lines="2"
    @echo off
    set OPENSSL_ia32cap=:~0x20000000

    pushd %~dp0
    ...
    ```

### 共享音频设置

!!! tip ""

    - 鼠标右键单击任务栏中的音量图标并选择**`声音`**选项

    - 选择**`高级`**选项卡

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0006.png" width = 400/> </div>

    - 在你的默认音频输出设备上双击鼠标左键，在弹出的属性窗口选择**`高级`**选项卡

    - 选择**`默认格式`**中的下拉菜单，选择**`24位，48000Hz（录音室音质）`**选项

    - 勾选**`独占模式`**下的两个选项，点击**`应用`**后选择**`确定`**

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0007.png" width = 400/> </div>

### 加快游戏启动速度

!!! tip ""

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0019.png"/> </div>

    如果启动游戏后在上图处等待很久，您可以将整个HDD文件夹添加到**`Windows Defender`**的**`排除项`**中可以加快游戏启动自检速度

    CHUNITHM 文件夹中包含有数千个xml文件，**Windows Defender** 需要很长时间才能扫描完这些文件

    - 在任务栏**`Windows 安全中心`**（小盾牌图标）上点击鼠标左键呼出安全中心界面

    - 左侧导航栏选择**`病毒和威胁防护`**，在右侧点击**`“病毒和威胁防护”设置`**下的**`管理设置`**选项

    - 向下滚动找到**`排除项`**，点击**`添加或删除排除项`**

    - 点击**`添加排除项`**将整个HDD文件夹加入后关闭安全中心即可

### 设置虚拟Aime卡号

!!! tip ""

    !!! note "保存游戏数据需要设置虚拟卡号文件，如果你有读卡器请直接刷卡"

    !!! warning "不建议自行编写卡号，这样有可能会与在线服的其他玩家撞卡，离线服无需注意"

    如何建立Aime卡号：

    在第一次启动游戏时，可在游戏标题处长按 **`Enter`** 刷卡，游戏会自动生成卡号文件

    如果你拥有20位Aime卡号，也可以自行建立卡号文件

    - 在 **`bin\DEVICE`** 文件夹中建立名为 **`aime`** 的文本文档文件 (aime.txt)

    - 打开此文件，填入你的卡号 (20位纯数字)，可以是你手中真实卡片背面的卡号 (ACCESS CODE)

    - 如果自行编写，则卡号不能以3开头

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0008.png" width = 400/> </div>

### 启动HDD

!!! tip ""

    !!! warning "从本节开始，如遇到各种问题，请首先查阅 **[常见问题](faq.md)** 、 **[错误代码](errorcodes.md) 与 [排除故障](troubleshooting.md)** 来尝试解决问题！"
    
    !!! danger "请不要运行HDD中的 **`game.bat`** ！！！"

    如果你完成了上述所有步骤，此处开始就可以启动HDD了

    - 运行**`bin\start.bat`**来启动HDD

    - 正常游戏会弹出3个窗口，分别为游戏主窗口、Log窗口、amdaemon窗口（inject）

    - 如果amdaemon窗口（inject）消失，请查看上面 **[修复 OpenSSL](#openssl)** 部分的设置

!!! tip "启动自检部分"

    在自检中通过全部网络测试即可正常联网，如下图：

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0009.png" width = 400/> </div>

    !!! warning "E-MONEY显示N/A为正常并不影响联网"

!!! tip ""

    - 在游戏自检进行到下图的时候，如果等候很久没有任何反应，则需要进入TEST菜单进行设置

        <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0010.png" width = 400/> </div>

        * 按下手台上对应TEST功能的按键，或**`segatools.ini`**中**`[io3]`**设置的对应按键，进入TEST菜单

        * 按下**`SERVICE`**按键选择菜单选项，按下**`TEST`**按键确定选项

    - 选择**`ゲーム設定`**

        <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0011.png" width = 400/> </div>

        * 选择**`グループ内基準機設定`**，将右侧**`基準機に従う`**切换为**`基準機`**

        * 启动接关功能将**`コンティニュー設定`**由**`OFF`**切换为**`ON`**

        * 选择**`終了`**返回TEST主菜单

    - 接下来选择**`閉店設定`**

        <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0012.png" width = 400/> </div>

        * 将**`スケジュール種別`**与**`時`**分别设置为**`每日`**与**`全時刻`**

        <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0013.png" width = 400/> </div>

        * 选择**`終了`**返回TEST主菜单

        * 选择TEST主菜单**`終了`**以继续

    - 待到LED自检时，双手需要离开AIR识别区域并且不要触碰触摸板，等待自检完成即可自动进入游戏标题界面

        <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0014.png" width = 400/> </div>

        * 如果此处**`LED制御ボード1·2`**显示为**`BAD`**请不要紧张，这并不影响游戏正常运行，请按右下角提示**`次へ`**按下触摸板跳过即可

        * **`LED制御ボード1·2`**显示为**`BAD`**请检查**`segatool.ini`**中**`[led]`**部分设置是否为**`enable=1`**

---

## 开始游戏

!!! note "见到下图画面的话，那么恭喜你已经正常联网并且可以开始游戏了！"

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0015.png"/> </div>

!!! tip ""

    - 请检查右下角版本号是否为**`Version 2.30`**，如果不对请返回 **[安装ICF](#icf)** 部分检查ICF文件是否安装正确

    - 请检查右下角网络状态图标是否为绿色 (另外一个图标是框体群组标识)

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0016.png" width = 400/> </div>

    - 网络自检全为GOOD但此处网络显示灰色图标，请返回 **[安装option](#option)** 部分检查是否安装正确的 **`option`**

    - 或尝试安装自制包 **`A999`** 到 **`option`** 中即可解决此问题

    - 在标题界面长按 **`Enter`** 或在读卡器刷卡即可登录进行游戏，按数字 **`3`** 或手台对应按键进行投币

!!! tip "下图为游戏画面"

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0017.png"> </div>

!!! note "至此，你已经可以正常进行游戏了"

    在游戏或配置过程中有疑问或问题，请带游戏或程序窗口或Log，ini设置等截图发送到对应群向群友或向其他玩家寻求帮助！

    <div align="center"> <img src="https://oss.am-all.com.cn/asset/img/manual/chu_manual/chum0018.png" width = 400/> </div>

---