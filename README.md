# Class2dex
#### 这是一个简单的基于android sdk制作的，可以将Java的class转为android的dex的工具
## 使用方法：
- 获取本工具 `git clone https://github.com/Lanthanum-system-toolbox-v2/Class2dex -b linux`
1. 将需要转换的文件名称改为in.jar，放置于class2dex同级目录
2. 终端运行`./class2dex`
3. 生成的out.jar即为转换结果

- 如果该out.jar要被作为一个镧·系统工具箱的模块，那么请将其名称改为与入口的class相同。
- 如入口为`public class Test implements LModule`,那么请将out.jar的名称改为Test.jar，否则无法被正常读取。
## 无法正常工作？
- 请配置完整的java环境。建议`sudo apt install openjdk-8-jre-headless`
