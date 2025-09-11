# 9.11 课程大纲

```mermaid

    graph LR
    W[大纲]
    W --> A
    W --> B
    A[ubuntu]
    a1[完全免费，开源透明
    **无隐藏后门、无强制广告、无隐私窃取风险**]
    a2[稳定性与可靠性
    **长期支持版本（LTS），确保系统的长期运行**]
    a3[对开发工具的原生支持
    **多数服务器端软件、编程语言、开发工具都优先支持**]
    a4[跨平台兼容性
    **支持多种架构，包括x86、ARM等**]
    a5[高度可定制化
    **用户可以根据需求自定义系统，Desktop、Server、Core等**]

    

    B[IDE]
    b1[IDE（集成开发环境，Integrated Development Environment） 是为开发者提供综合开发工具的软件应用]
    b11[代码编辑器（支持语法高亮、自动补全）]
    b12[编译器 / 解释器]
    b13[调试器（帮助开发者定位和修复错误）]
    b14[项目和文件管理]
    b15[插件扩展支持]

    b151[特定编程语言支持（语法高亮、补全、调试）]
    b152[代码格式化和风格检查]
    b153[版本控制增强]
    b154[文档预览,如 Markdown]
    b155[远程开发支持等**ssh**]
    A --> a1
    A --> a2
    A --> a3
    A --> a4
    A --> a5
    B --> b1

    b1 --> b11
    b1 --> b12
    b1 --> b13
    b1 --> b14
    b1 --> b15
    b15 --> b151
    b15 --> b152
    b15 --> b153
    b15 --> b154
    b15 --> b155

```

## 其它操作

- 更换软件源
- 打开shell配置文件
  - 打开终端
  - 输入`nano ~/.bashrc`
  - 输入`alias xx='nano ~/.bashrc`
  - 输入`source ~/.bashrc`
- git的安装
- vscode的安装
- git clone https://github.com/waliwuao/tutorial_ares.git
- 安装Markdown Preview Enhanced插件

