## 使用方法

1. 修改`_config.yml`文件中的内容

```
# 个人名称或昵称
name: chenanyi
# 页面个人头像信息中地址展示信息
location: 青岛
# 页面个人头像信息中公司展示信息
company: 青岛港
# 页面个人头像信息中职位展示信息
position: Java开发工程师
# 页面个人头像信息中GITHUB展示信息
github: https://github.com/XXXX
# 页面个人头像信息中Facebook展示信息
facebook: https://www.facebook.com/XXXX
# 页面个人头像信息中电话展示信息
phone: 1866970XXXX
# 页面个人头像信息中EMAIL展示信息
email: xxxx@xxx.com

#本项目的baseurl
baseurl: "/resume"
```

2. 修改个人头像信息

	修改 `_config.yml` 文件中内容

3. 修改基本信息
 
	修改 `_includes/resumer_01-basic.html` 文件中内容

4. 修改职业技能

    修改 `_includes/resumer_02-profetional.html` 文件中内容

5. 修改教育经历

    修改 `_includes/resumer_03-education.html` 文件中内容

6. 修改工作经历

    修改 `_includes/resumer_04-experience.html` 文件中内容

## 本地搭建

在本地安装[Jekyll](https://jekyllrb.com/).
然后在项目目录执行`jekyll s`命令,如下

```bash
[root@localhost ~]# jekyll s
Configuration file: C:/..../resume/_config.yml
            Source: C:/..../resume
       Destination: C:/..../resume/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
                    done in 0.371 seconds.
  Please add the following to your Gemfile to avoid polling for changes:
    gem 'wdm', '>= 0.1.0' if Gem.win_platform?
 Auto-regeneration: enabled for 'C:/..../resume'
    Server address: http://127.0.0.1:4000/resume/
  Server running... press ctrl-c to stop.
```

然后可以访问[http://127.0.0.1:4000/resume/](http://127.0.0.1:4000/resume/)来访问本地的服务了。


## 参考

本简历模板基于[Funday](https://gitee.com/xiaodan_yu/resume.io)修改而来。保留了所有的样式，基于Jekyll重构了页面框架，并去掉了一些没有必要的内容，整合一页简历。

