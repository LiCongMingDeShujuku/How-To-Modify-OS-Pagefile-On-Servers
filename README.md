![CLEVER DATA GIT REPO](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/0-clever-data-github.png "李聪明的数据库")

# 如何在服务器上修改OS Pagefile
#### How To Modify OS Pagefile On Windows Servers

![如何在服务器上修改OS Pagefile](images/How-To-Modify-OS-Pagefile-On-Servers.png?raw=true "如何在服务器上修改OS Pagefile")

## Contents

- [中文](#中文)
- [English](#English)
- [Build Info](#Build-Info)
- [Author](#Author)
- [License](#License) 


## 中文
转到Start à Run:：systempropertiesadvanced
1. 单击“Advanced”
2. 单击“Settings”
3. 单击“Advanced”
4. 点击“Change”
5. 取消“Automatically manage paging file size for all drives”选项。 （在这种情况下，我们只有一个驱动器）
6. 选择“Custom size”，然后进行大约10GB的设置（输入10240）
为了使改变生效，需要重启。



## English
Sometimes you’ll need to clear some space from the OS drive on the Server. One of which is constant, but doesn’t have to be that way; is the paging file. Yeah; sure… the page file has a purpose, but it doesn’t have to consume more than 10 – 20GB of space. Here’s how to modify it.

消耗超过10-20GB的空间。 这是修改它的方法。
Go to Start à Run: systempropertiesadvanced
1. Click ‘Advanced’
2. Click ‘Settings’
3. Click ‘Advanced’
4. Click ‘Change’
5. Uncheck the option for ‘Automatically manage paging file size for all drives’. (In this case we only have one drive anyway)
6. Select ‘Custom size’, and make the setting about 10GB ( Type in 10240 )
In order for the change to take affect; a reboot is needed.





[![WorksEveryTime](https://forthebadge.com/images/badges/60-percent-of-the-time-works-every-time.svg)](https://shitday.de/)

## Build-Info

| Build Quality | Build History |
|--|--|
|<table><tr><td>[![Build-Status](https://ci.appveyor.com/api/projects/status/pjxh5g91jpbh7t84?svg?style=flat-square)](#)</td></tr><tr><td>[![Coverage](https://coveralls.io/repos/github/tygerbytes/ResourceFitness/badge.svg?style=flat-square)](#)</td></tr><tr><td>[![Nuget](https://img.shields.io/nuget/v/TW.Resfit.Core.svg?style=flat-square)](#)</td></tr></table>|<table><tr><td>[![Build history](https://buildstats.info/appveyor/chart/tygerbytes/resourcefitness)](#)</td></tr></table>|

## Author

- **李聪明的数据库 Lee's Clever Data**
- **Mike的数据库宝典 Mikes Database Collection**
- **李聪明的数据库** "Lee Songming"

[![Gist](https://img.shields.io/badge/Gist-李聪明的数据库-<COLOR>.svg)](https://gist.github.com/congmingshuju)
[![Twitter](https://img.shields.io/badge/Twitter-mike的数据库宝典-<COLOR>.svg)](https://twitter.com/mikesdatawork?lang=en)
[![Wordpress](https://img.shields.io/badge/Wordpress-mike的数据库宝典-<COLOR>.svg)](https://mikesdatawork.wordpress.com/)

---
## License
[![LicenseCCSA](https://img.shields.io/badge/License-CreativeCommonsSA-<COLOR>.svg)](https://creativecommons.org/share-your-work/licensing-types-examples/)

![Lee Songming](https://raw.githubusercontent.com/LiCongMingDeShujuku/git-resources/master/1-clever-data-github.png "李聪明的数据库")

