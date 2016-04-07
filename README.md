activate-power-mode
====

activate-power-mode for IDEA
-------

####下载
>git clone https://github.com/ViceFantasyPlace/activate-power-mode.git

####第一次运行如果没有运行配置需要创建一个Plugin的Configuration
>Edit Run/Debug Configurations <br>
>-> add a new Plugin Configuration <br>
>-> 在 Use classpath of module 选择 activate-power-mode <br>
>-> Apply <br>

注意，编译的时候jdk1.8.
找到 /Applications/IntelliJ IDEA XXX.app/Contents/Info.plist file. 修改 JVMVersion 从 1.7* 到 1.8*。
  <key>JVMVersion</key>
  <string>1.8*</string>

