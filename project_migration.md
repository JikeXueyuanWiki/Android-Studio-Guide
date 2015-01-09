# 将Eclipse中项目迁移到Android Studio中

1. 从Eclipse中导出项目
2. 将项目导从Eclipse 导入到Android Studio中

根据官方的介绍，Android Studio 可以兼容 Eclipse 的现有工程，但需要做一些操作：

**1.** 首先升级ADT到最新版本，目前为版本号为22（注意和ADT相关的组件最好一并升级，避免后期可能出现的错误）   

**2.** 选择需要从Eclipse导出的工程，右键选择Export并选择Android下的Generate Gradle Build Files（如下图）：      

eclipse_1图片

选择完毕后，并不会导出到其他地方，而是在本地工程生成了一个build.gradle文件，在Eclipse工程中也可以看到，这个文件是Android Studio识别的，如下图：      

eclipse_2图片     

**3.** 随后进入Android Studio 并选择ImportProject，可以看到刚刚在Eclipse中的项目图标变成了一个Android机器人图标，说明转换成功，这时候选择工程导入即可：        

eclipse_3图片       

至此，就完成了从Eclipse导入现有Android工程到Android studio，现在可以开始对工程进行操作了！

