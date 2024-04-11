# mip
mock interview platform

常见的分支命名模式
功能（Feature）分支：

命名规则：feature/<功能名称>
用途：用于开发新功能。
例子：feature/login-system, feature/payment-integration
修复（Bugfix）分支：

命名规则：bugfix/<bug描述>
用途：用于修复错误。
例子：bugfix/crash-on-launch, bugfix/wrong-calculation
发布（Release）分支：

命名规则：release/<版本号>
用途：用于准备发布的版本，进行最后的调整和测试。
例子：release/1.0.0, release/1.1.0
维护（Hotfix）分支：

命名规则：hotfix/<issue>
用途：用于对生产中的版本进行紧急修复。
例子：hotfix/urgent-fix-login, hotfix/2.0.1
开发（Develop）分支：

命名规则：通常就是 develop 或 dev
用途：用于日常开发的主分支。
主（Master/Main）分支：

命名规则：通常是 master 或最近更常见的 main
用途：存放已发布到生产环境的代码，保持最高级别的稳定和可靠性。
最佳实践
简洁明了：分支名称应简洁且富有描述性。
使用斜杠分隔功能：使用斜杠（/）来分隔分支类型和描述，如 feature/ 或 bugfix/。
避免空格：不要在分支名中使用空格；使用连字符（-）或下划线（_）作为单词分隔符。
规避特殊字符：避免使用 Git 可能解析错误的特殊字符。
通过实施这样的命名模式，团队可以更加高效地管理和维护项目的不同阶段和特性开发。


