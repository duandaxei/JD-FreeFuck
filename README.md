__如果您觉得这个项目不错的话可以在右上角给颗⭐吗？您的支持是我最大的动力，方便分享给更多的朋友吗？__

***

## 通知与更新
> `更新` 代表有新的内容增加，您可以更新也可以继续使用之前的版本，不影响当前使用，除非说明需要重新部署\
> `修复` 代表有错误已经修复完毕需要您执行相关命令解决相应的问题，如有特殊命令需要执行会在 Wiki 首页发布\
> `通知` 代表有新的内容或信息需要您了解，请确保已仔细阅读所有通知内容\
> 具体内容和命令请前往《使用与更新》教程或 [Wiki首页](https://github.com/SuperManito/JD-FreeFuck/wiki/) 查看

- __2021/3/11 20:00 `更新`__
ㅤ更新了配置文件，版本号到`3.32.5`，新增 "定义京喜农场控制通知推送级别" 控制脚本功能环境变量；更新了DIY脚本，新增部分活动。

- __2021/3/11 14:30 `通知`__
ㅤ目前检测到 `Linux` 版本新安装用户定时重复的问题，原因是由于在9号的更新中调整了部署脚本的安装顺序，目前已经修复了部署脚本。如果您在最近的两天内安装了`Linux` 版本，自行删除重复的定时内容即可，定时任务不会再次添加重复任务，本身也不影响其正常执行。`Docker ` 版用户请忽略此通知。

- __2021/3/11 04:00 `更新`__
ㅤ同步上游源码更新了 `格式化导出互助码脚本`，现在更好用了；优化了控制面板的排版和底层代码，请所有朋友执行 `git_pull` 一键更新脚本，然后根据对应版本《使用与更新》教程之<控制面板教程>的第6条命令升级，最后根据第3条命令重启控制面板完成更新。本项目前致力于开发控制面板，遇到问题请立即反馈，感谢您的理解与支持。

- __2021/3/09 06:00 `更新与修复`__\
ㅤ1. 更新了控制面板，手动执行模块新增多个功能 \
ㅤ2. 修复了 `Linux` 版无法使用控制面板手动执行模块的问题 \
ㅤ3. 变更了一键执行所有活动脚本的命名，注意今后使用新命令 

- __2021/3/07 04:30 `更新`__\
ㅤ1. 更新了一键更新脚本，新增同步项目Shell脚本功能，从而减少未来项目更新后的手动操作。\
ㅤ2. 修复了在启用diy脚本后重复输出删除定时任务的问题。\
ㅤ3. 更新了配置文件，将DIY脚本同步地址变量移入至配置文件中。

***

# __《JD薅羊毛》一键部署 For Linux__
- __用途：通过自动化脚本参与JD商城的各种活动从而获取京豆用于购物抵扣<br>ㅤㅤㅤ还可通过某些活动免费领取商品或现金红包__
- __适用平台：PC、VPS (虚拟专用服务器) 、NAS 、软路由__
- __适用环境：GNU/Linux & Docker Server__

__ㅤㅤ`Telegram` 通知频道：[ t.me/jd_freefuck ](https://t.me/jd_freefuck)__

__ㅤㅤ`码云Gitee` 同步更新：[ 点击此处访问 ](https://gitee.com/SuperManito/JD-FreeFuck)__

## 特别声明：

* 本仓库发布的项目中涉及的任何解锁和解密分析脚本，仅用于测试和学习研究，禁止用于商业用途，不能保证其合法性，准确性，完整性和有效性，请根据情况自行判断。

* 本项目内所有资源文件，禁止任何公众号、自媒体进行任何形式的转载、发布。

* `SuperManito` 对任何脚本问题概不负责，包括但不限于由任何脚本错误导致的任何损失或损害。

* 间接使用脚本的任何用户，包括但不限于建立VPS或在某些行为违反国家/地区法律或相关法规的情况下进行传播，`SuperManito` 对于由此引起的任何隐私泄漏或其他后果概不负责。

* 请勿将项目中的任何内容用于商业或非法目的，否则后果自负。

* 如果任何单位或个人认为该项目的脚本可能涉嫌侵犯其权利，则应及时通知并提供身份证明、所有权证明，我将在收到认证文件后删除相关脚本。

* 任何以任何方式查看此项目的人或直接或间接使用该项目的任何脚本的使用者都应仔细阅读此声明。

* `SuperManito` 保留随时更改或补充此免责声明的权利，一旦使用并复制了任何相关脚本或项目的规则，则视为您已接受此免责声明。

* 您必须在下载后的 `24小时` 内从计算机中完全删除以上内容。

***

> ***您使用或者复制了本仓库且本人制作的任何脚本，则视为 `已接受` 此声明，请仔细阅读*** 

***

## 项目声明：

* 本项目开源免费使用，如果您在其它任何地方发现以 `付费` 的形式 `传播与使用` 请积极抵制并向我反馈，举报有奖。

* 本项目代码各处均有注释其含义，所有脚本中没有附加、偷跑任何互助码，无任何第三方链接，无任何私利。

* 本项目基于 [Evine](https://gitee.com/evine) 前辈开发的源码而制作，包括 `Docker` 版所使用的镜像，后续的维护与更新均建立于此之上。

* 本项目所使用的活动脚本均由 [lxk0301](https://gitee.com/lxk0301) 大佬提供，我不是活动脚本的开发者，所有与活动相关的问题均与我无关。

* 如果您对活动脚本提出疑问或建议想要反馈您的问题，请咨询活动脚本作者，我可能无法为您提供有价值的信息。

* 本项目不可 `分享与传播` 在国内平台的媒体与网站上，不得进入普通大众的视野，所有媒体分享本项目时请注明来源。

* 为了维持本项目的稳定运作，请勿 `传播与使用` 本项目中被第三者修改过的脚本，请勿滥用 `平台资源` 等使用行为。
ㅤ

***

__请ㅤㅤ认ㅤㅤ真ㅤㅤ阅ㅤㅤ读ㅤㅤ教ㅤㅤ程ㅤ，ㅤ90%ㅤㅤ的ㅤㅤ问ㅤㅤ题ㅤㅤ都ㅤㅤ能ㅤㅤ找ㅤㅤ到ㅤㅤ答ㅤㅤ案__

***

## 一、前言
#### 1. 本项目根据安装平台区分为 `Linux` 与 `Docker` 两个版本，分别提供对应的脚本文件与教程
#### 2. `Linux` 为系统直装版本，适配常用 `GNU/Linux` 发行版，仅适用于在 `PC`  `VPS` 平台部署
#### 3. `Docker` 为容器版本，且为通用版本，建议用于在 `NAS`  `软路由` 平台部署，占用资源较低
#### 4. 两版本的《部署教程》与《使用教程》均不相同，不要错误、重复使用，请认真阅读所有内容

***

## 二、项目部署

***

> 下面是 `Linux` 版本的部署教程，执行命令前请认真阅读注释内容，不要执行错误的命令！

***

### `Linux` 版本
> 仅支持 `Debian` 与 `Redhat` 发行版和及其衍生发行版\
> 尽量使用最新的稳定版系统，并且安装语言使用 `简体中文`\
> 否则请使用 `Docker` 通用版本部署此项目\
> 附：[ Windows10 安装 WSL Ubuntu 教程](https://github.com/SuperManito/JD-FreeFuck/wiki/Windows10-Install-WSL-Ubuntu)
#### __部署前需知与准备工作：__
1. 执行命令前请检查您当前环境是否联网，并请切换至 `root` 用户，切换命令为 `sudo -i`。
2. 如果您使用的是 CentOS 系统且最小化安装，请通过 SSH 的方式进入到终端。
3. 本项目默认安装目录为 `/opt/jd` ，如果您不想安装到该目录请自行下载部署脚本并更改相关变量手动部署。
4. 由于某些组件的安装受国外网络影响，如果部署失败或遇到报错请再次尝试，否则请严格按照模板提交至 Issues 寻求帮助。
5. 若您使用 `VPS` 平台，部署前请进入您所使用平台提供商的防火墙功能，检查是否已开放相关端口、允许`HTTP/HTTPS`流量通过等设置。
6. `控制面板` 功能的初始用户名为 `useradmin`，初始密码为 `supermanito`，部署成功后可通过 `http://内部或外部IP地址:5678` 访问。
7. 如果您使用平台的网络环境暴露在了公网，请根据教程更改 `控制面板` 的用户名、密码、启动端口号，否则造成的信息泄露后果自负。
8. 若您使用 `VPS` 平台，关机前请先手动执行相关命令停止控制面板的运行，否则在仪表盘强制关机重启后该功能可能会出现异常。

#### __更换国内源：（选择执行）__
    bash <(curl -sSL https://gitee.com/SuperManito/LinuxMirrors/raw/main/ChangeMirror.sh)
> _注意：1. 此脚本为本人原创的 `一键更换国内更新源脚本` ，此处调用本人另一个原创项目中的脚本文件，_\
> _ㅤㅤㅤ2. 脚本自带备份功能，无需手动备份原有官方源，此脚本之前附加在旧版本部署脚本中现独立出来，_\
> _ㅤㅤㅤ3. 如果您使用平台的地区位于国外则不需要执行此脚本，例如 `Google Cloud Platform` 用户，_\
> _ㅤㅤㅤ4. 此脚本并没有适配所有的 GNU/Linux 发行版和版本号，具体支持列表详见下方表格。_
- 可使用 `ChangeMirror` 一键更换国内源脚本的 GNU/Linux 发行版：

| 操作系统  |    支持的版本   |
| :------: | :------------: |
| Ubuntu   | 18.04 ~ 20.10  |
| Debian   | 9.0 ~ 10.8     |
| Fedora   | 28 ~ 33        |
| CentOS   | 7.0 ~ 8.3      |
| Kali     | 2019 ~ 2021.1  |
> 友情提示：如果您的系统或版本不在此列表中则无法使用此脚本，即时误执行也不会有任何的更改
#### __脚本一键部署：__
    bash <(curl -sSL https://gitee.com/SuperManito/JD-FreeFuck/raw/main/install.sh)
#### __常见问题与帮助：__
1. 如果执行部署脚本命令后提示 `Command 'curl' not found` 则说明当前未安装 `curl` 软件包，安装命令如下：

       apt install -y curl 或 yum install -y curl
2. 如果执行脚本部署命令后没有反应直接结束并跳回终端交互说明您的网络环境存在问题，请检查您的网络连通性。
3. 如在拉取活动脚本时失败提示 `ssh: connect to host gitee.com port 22: Connection timed out` 是由于您使用平台的 `22` 端口不可用所导致，自行解决处理。
4. 如在拉取活动脚本时失败提示 `Repository more than 5 connections` 是由于 `Gitee` 限制了每秒同时拉取项目的IP不能超过 `5` 个所导致，此报错为正常现象，重新执行更新命令即可。
5. 部署成功后无法访问 `控制面板` 浏览器提示 `无法访问此网站` 是由于 `5678` 端口外部不能访问所导致。
6. 如果 `控制面板` 功能未安装成功可执行下面的命令重新安装：

       cd /opt/jd/panel
       npm install || npm install --registry=https://registry.npm.taobao.org
       npm install -g pm2
       pm2 start ecosystem.config.js
ㅤ

***

> 下面是 `Docker` 版本的部署教程，执行命令前请认真阅读注释内容，不要执行错误的命令！

***

### `Docker` 版本
### 支持的架构：
`amd64` `arm64` `arm/v8` `arm/v7` `arm/v6` `ppc64le` `s390x`
#### __部署前需知与准备工作：__
1. 执行命令前请检查您当前环境是否联网，并请切换至 `root` 用户，切换命令为 `sudo -i`。
2. 下面的教程涉及 `容器技术` 专业知识，执行命令前请先看 `注释内容` ，若无法理解请先自行百度查询。
3. 使用 `NAS` `软路由` 的朋友请在终端执行下面教程中的命令，不要使用图形界面，复制命令时请复制完整不要自作聪明。
4. 若您使用 `VPS` 平台，部署前请进入您所使用平台提供商的防火墙功能，检查是否已开放相关端口、允许`HTTP/HTTPS`流量通过等设置。
5. `控制面板` 功能的初始用户名为 `useradmin`，初始密码为 `supermanito`，部署成功后可通过 `http://内部或外部IP地址:5678` 访问。
6. 如果您使用平台的网络环境暴露在了公网，请根据教程更改 `控制面板` 的用户名、密码、启动端口号，否则造成的信息泄露后果自负。
7. 若您使用 `VPS` 平台，关机前请先手动执行相关命令停止控制面板的运行，否则在仪表盘强制关机重启后该功能可能会出现异常。

#### __安装 Docker Server 客户端：__

    curl -sSL https://get.daocloud.io/docker | sh
> _注意：部分设备默认自带 `Docker` 客户端，如果没有安装请先执行此官方脚本一键安装。_
#### __下载镜像：__
    docker pull registry.cn-hangzhou.aliyuncs.com/supermanito/jd
> _注意：此镜像大约需要占用 `239MB` 的空闲存储空间，目前最新版本的镜像ID为 `d9df47b78ff6` 。_
#### __启动容器：__
    docker run -dit \
    -v /opt/jd/scripts:/jd/scripts `# 设置活动脚本的主机挂载目录为/opt/jd/scripts` \
    -v /opt/jd/config:/jd/config `# 设置配置文件的主机挂载目录为/opt/jd/config` \
    -v /opt/jd/log:/jd/log `# 设置日志文件的主机挂载目录为/opt/jd/log` \
    -p 5678:5678 `# 设置端口映射，格式为 "主机端口:容器端口"，主机端口号可自定义` \
    -e ENABLE_HANGUP=true `# 启用挂机功能` \
    -e ENABLE_WEB_PANEL=true `# 启用控制面板功能` \
    --name jd `# 设置容器名为 jd ` \
    --network bridge `# 设置容器网络类型为桥接，直连主机` \
    --hostname jd `# 设置容器内主机名为 jd ` \
    --restart always `# 设置容器开机自启` \
    registry.cn-hangzhou.aliyuncs.com/supermanito/jd
> 友情提示：请完整复制上面的命令，如果您不了解 `Docker` 容器技术，不要自作聪明删减后面的注释内容

> _注意：1.如果是旁路由，容器网络类型需使用ㅤ`host` 模式，请将 `--network bridge` 参数改成 `--network host`，_\
> _ㅤㅤㅤ2.如果设备不存在 `opt` 目录，请先通过命令 `mkdir -p /opt/jd` 创建主机目录，您也可以自定义挂载目录，_\
> _ㅤㅤㅤ3.如果您想将挂载目录替换为当前所在目录，将 `/opt/jd` 参数改成 `$PWD` 即可，注意不要忽略后面的文件夹，_\
> _ㅤㅤㅤ4.如果您想多台容器，将容器名修改为其它名称即可，后续使用中的命令参数也需要随之更改。_
#### __初始化容器：__
    docker logs -f jd
> _注意：请先执行此命令查看容器初始化进度，当输出 `容器启动成功......` 字样时即代表容器启动正常，此时通过命令 `Ctrl + C` 退出即可。_
#### __常见问题与帮助：__
1. 如在拉取活动脚本时失败提示 `ssh: connect to host gitee.com port 22: Connection timed out` 是由于您使用平台的 `22` 端口不可用所导致，自行解决处理。
2. 如在拉取活动脚本时失败提示 `Repository more than 5 connections` 是由于 `Gitee` 限制了每秒同时拉取项目的IP不能超过 `5` 个所导致，此报错为正常现象，重新执行更新命令即可。
3. 部署成功后无法访问 `控制面板` 浏览器提示 `无法访问此网站` 是由于容器映射的 `主机端口` （默认5678）外部不能访问所导致。
4. 如果 `控制面板` 功能未安装成功可执行下面的命令重新安装：

       docker exec -it jd /bin/bash
       cd panel
       yarn install || yarn install --registry=https://registry.npm.taobao.org
       npm install -g pm2
       pm2 start ecosystem.config.js
       exit

***

## 三、配置项目

***

> 接下来需要您JD账户的“身份证”，它由 `Cookie部分内容` 组成，将它写入至配置文件中才可以开始使用\
> 此部分教程的配置操作也可在 `控制面板` 功能中的 `WEB网页` 完成配置，可取代在终端输入命令，适合小白

***

#### 关于获取账户信息的途径：
- 通过 `控制面板` 功能进入 `WEB网页` 手机APP扫码获取，获取后可直接在配置文件中配置 __（优先推荐）__
- 通过浏览器 `开发工具` 获取，请前往 Wiki 查看具体的图文教程ㅤ[点击此处前往](https://github.com/SuperManito/JD-FreeFuck/wiki/GetCookies1)
- 通过浏览器 `扩展插件` 获取，请前往 Wiki 查看具体的图文教程ㅤ[点击此处前往](https://github.com/SuperManito/JD-FreeFuck/wiki/GetCookies1)
> 所有方式获取的 `Cookie` 有效期均为1个月，过期后活动脚本会有提示，届时您需要手动更新您的账户信息
#### __配置账户信息：__
- 将获得的 `Cookie部分内容` 填入下面命令中的 `"双引号"` 内，然后复制完整命令到终端并执行：

      sed -i '30c Cookie1=""' config/config.sh
      sed -i '31c Cookie2=""' config/config.sh
      sed -i '32c Cookie3=""' config/config.sh
      sed -i '33c Cookie4=""' config/config.sh
      sed -i '34c Cookie5=""' config/config.sh
      sed -i '35c Cookie6=""' config/config.sh
> _参考命令：`sed -i '30c Cookie1="pt_key=xxxxxxx;pt_pin=xxxxx;"' config/config.sh`_

> _注意：1. 执行此命令前 `Linux` 版需要进入项目安装目录，`Docker` 版需要进入容器内，_\
> _ㅤㅤㅤ2. 用几个账号就执行几行命令，此操作对应配置文件中的第 30~35 行内容，_\
> _ㅤㅤㅤ3. 超出6个账号后需要自行在 `config.sh` 配置文件中创建变量，各个账号之间不能有空变量，_\
> _ㅤㅤㅤ4. 否则从空变量起下面的账号将不能被识别，例如 Cookie2 没有填则 Cookie3 及以下的所有账号都不能被识别。_
#### __配置消息推送：__（可选）
> _详见 `config.sh` 配置文件中 `推送通知环境变量` 板块的注释内容，教程很详细......_

***

## 四、使用项目
#### __使用与更新教程：__
- __`Linux` 版本ㅤㅤ[点击此处前往](https://github.com/SuperManito/JD-FreeFuck/wiki/Linux-Use-And-Update-Tutorial)__
- __`Docker` 版本 ㅤ[点击此处前往](https://github.com/SuperManito/JD-FreeFuck/wiki/Docker-Use-And-Update-Tutorial)__
> _注意：您使用的是哪个版本就用哪个版本的教程，不要错用、混用，更不要擅自使用本项目之外的教程命令，否则出现问题后果自负！_
#### __项目通知：__
- 项目后续的 `更新` `修复` `通知` 都会在项目页置顶，请保持关注本项目或订阅 `Telegram` 通知频道
> `更新` 代表有新的内容增加，您可以更新也可以继续使用之前的版本，不影响当前使用，除非说明需要重新部署\
> `修复` 代表有错误已经修复完毕需要您执行相关命令解决相应的问题，如有特殊命令需要执行会在 Wiki 首页发布\
> `通知` 代表有新的内容或信息需要您了解，请确保已仔细阅读所有通知内容

***

## 五、卸载项目
#### `Linux` 版本
- 停止控制面板与后台挂机程序的运行：

      pm2 stop /opt/jd/panel/ecosystem.config.js
      pm2 stop crazy_joy_coin
- 删除项目文件：

      rm -rf /opt/jd
- 卸载已安装的软件包：

      apt remove -y git perl moreutils nodejs npm 或 yum remove -y git perl moreutils nodejs npm
#### `Docker` 版本
- 停止控制面板运行：

      docker exec -it jd /bin/bash pm2 stop panel/ecosystem.config.js
- 删除容器：

      docker rm -f jd
- 删除容器挂载目录：

      rm -rf /opt/jd
- 删除镜像：

      docker rmi -f registry.cn-hangzhou.aliyuncs.com/supermanito/jd
> __若您 `已接受` 本项目中的声明，您必须在下载后的 `24小时` 内从计算机中完全删除相关内容。__

***

## 六、帮助与支持
- __如果您有意见与建议或者遇到问题需要我的协助，欢迎到 [Issues](https://github.com/SuperManito/JD-FreeFuck/issues) 提交您的反馈__
- __为了提高效率快速解决您的问题，请严格按照模板提交，感谢您的理解与配合__

***

## 明天会更好
<img src="https://gitee.com/SuperManito/JD-FreeFuck/raw/main/icon/thank.jpg" width="300" height="300" alt="微信赞赏码"/><br/>
### 开发不易、维护艰辛，如果您愿意支持此项目，可对我打赏，感激不尽！

***

## Stargazers over time
<img src="https://starchart.cc/SuperManito/JD-FreeFuck.svg" width="500" height="250" alt="Stargazers over time"/><br/>

***

__如果您觉得这个项目不错的话可以在右上角给颗⭐吗？您的支持是我最大的动力，方便分享给更多的朋友吗？__
