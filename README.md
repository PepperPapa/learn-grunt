gruntxx
=======

Grunt 新手一日学会 配套示例项目。

详情请看文章：<http://yujiangshui.com/grunt-basic-tutorial/>

切换到 grunt 分支有惊喜。


关键说明：
1.sass任务需要有ruby和sass环境支撑，否则即使安装相应的插件也会报错。
windows环境下可以使用http://rubyinstaller.org/进行安装，安装完毕后即拥有ruby和gem包管理环境，cmd下执行gem install sass即可安装sass环境，如果报错多执行几次。
2.如下代码option选项是为了忽略压缩js代码函数间添加分号;会报错的提示。
jshint: {
      options: {
        '-W032': false,
      },
      all: ['./global.js']
    },