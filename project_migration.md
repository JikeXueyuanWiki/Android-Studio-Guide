# 将Eclipse中项目迁移到Android Studio中
1.从Eclipse中导出项目
2.将项目导从Eclipse 导入到Android Studio中
根据官方的介绍，Android Studio 可以兼容 Eclipse 的现有工程，但需要做一些操作：2.1首先升级ADT到最新版本，目前为版本号为22（注意和ADT相关的组件最好一并升级，避免后期可能出现的错误）
2.2选择需要从Eclipse导出的工程，右键选择Export并选择Android下的Generate Gradle Build Files（如下图）：
