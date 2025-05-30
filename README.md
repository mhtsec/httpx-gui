# HTTPX-GUI

HTTPX-GUI是对命令行工具[httpx](https://github.com/projectdiscovery/httpx)的图形界面，保留了原工具的所有功能，原理是调用本地命令行的httpx，使其更易于使用。

## 功能特点

- 简洁美观的用户界面
- 支持所有httpx命令行参数
- 实时输出结果
- 保存结果到文件
- 支持批量URL/主机处理
- 多种HTTP探测选项
- ![image](https://github.com/user-attachments/assets/24645879-e6b8-4984-b10e-0bba66a1caee)
- ![image](https://github.com/user-attachments/assets/058684ce-d8fc-4df4-98fe-f0fa7d93c544)
![image](https://github.com/user-attachments/assets/e07c964d-c6c0-4557-9041-b55dcab2a7ee)
![image](https://github.com/user-attachments/assets/cd2fb960-28c8-4c3c-a7f9-8f66fc3968b5)
![image](https://github.com/user-attachments/assets/bf8426b7-f6c6-432a-9d30-1ce989a7e713)
![image](https://github.com/user-attachments/assets/d1849321-8818-44f8-9031-da25276bb52e)

## 安装

### 二进制下载

您可以从[Releases页面](https://github.com/projectdiscovery/httpx/releases)下载预编译的二进制文件。

## 使用方法

1. 启动应用后，您将看到主界面，分为三个选项卡：基本、高级和输出。
2. 在"基本"选项卡中：
   - 选择输入类型（URL/主机或文件）
   - 输入目标URL或选择包含目标的文件
   - 选择要使用的探测选项
3. 在"高级"选项卡中，您可以设置：
   - 线程数和速率限制
   - 输出文件
   - 匹配和过滤状态代码
   - 自定义头和路径
4. 点击"运行"按钮开始扫描
5. 结果将显示在"输出"选项卡中

## 依赖

- httpx命令行工具（确保已安装并可在PATH中访问）
- windows中httpx安装到命令行：
- ![image](https://github.com/user-attachments/assets/6ddf5ecf-e9d8-49d1-8c6b-214969e183d5)


## 注意事项

- HTTPX-GUI仅是命令行工具httpx的图形界面封装
- 所有处理逻辑由httpx核心库完成
- 使用过程中需注意网络安全，遵守相关法律法规

