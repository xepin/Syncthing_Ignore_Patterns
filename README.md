# Syncthing Ignore Patterns

Syncthing 同步工具的忽略清单位于各同步目录内的 .stignore

可在Syncthing配置文件的忽略清单里设置，或编辑 .stignore 来设置。


支持的通配符的简单教程：

(?d)     表示如果删除了阻止目录则文件可被删除的前缀

(?i)     表示该模式匹配忽略了大小写差异的前缀

!        对本条件取反（例如：不要排除某项）

*         单级通配符（仅匹配单层文件夹）

**        多级通配符（用以匹配多层文件夹）

//       注释，在行首使用

