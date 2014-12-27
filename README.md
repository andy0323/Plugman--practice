# plugman-practice

本篇文章简单介绍了plugman、如何使用它进行插件安装、删卸、更新。

## 目录

1. 工具安装 
*  插件安装
*  插件删卸

### 工具安装

通过npm进行插件安装、在终端中调用下列指令，即可安装plugman。

	npm install -g plugman

### 如何安装

```
plugman install --platform ios --project . --plugin cordova-plugin-battery-status
```

### 如何删卸

```
plugman uninstall --platform ios --project . --plugin cordova-plugin-battery-status
```

## Contact
**Email:** andy_ios@163.com


##Licenses

All source code is licensed under the [MIT License](https://github.com/andy0323/JXRegular/blob/master/LICENSE).