# GradleUpdateDependencies
  通过自定义的 gradle task 获取项目依赖库的最新的release版本， 方便开发人员升级依赖库
# Getting Started

  要保证你本地gradle环境配置过,可以用gradle -v 测试环境变量是否已配置.<br/>
  
  1.把task.gradle文件拷贝到的项目根目录下.
  
  2.在app module 的build.gradle文件里，添加 apply from:'../task.gradle'.
  
  3.在项目目录下输入命令 gradle gradleReport(或者gR) 即可执行脚本.
  
  
![image](https://github.com/qingyunchinese/gradleUpdateDependencies/blob/master/design_sketch.png)  
  
  
