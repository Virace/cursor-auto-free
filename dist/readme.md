

# Cursor Pro Keep Alive 使用说明文档

## 1. 软件介绍
Cursor Pro Keep Alive 是一个自动化工具，用于管理 Cursor 账号的注册和更新。该工具可以自动执行账号删除和重新注册流程，以保持账号活跃。

## 2. 安装和准备

### 2.1 必要文件
确保您有以下文件：
- `cursor_pro_keep_alive.exe` - 主程序
- `config.ini` - 配置文件
- `turnstilePatch` - 插件文件夹

### 2.2 文件结构
```
your_folder/
├── cursor_pro_keep_alive.exe
├── config.ini
└── turnstilePatch/
    └── (插件文件)
```

## 3. 配置文件设置

在运行程序前，需要正确配置 `config.ini` 文件：

```ini
[Account]
email = your_username@mailto.plus    # 邮箱地址（必须使用 mailto.plus 域名）
password = your_password             # 账号密码
first_name = your_firstname          # 名字
last_name = your_lastname           # 姓氏
```

注意事项：
- 邮箱必须使用 `mailto.plus` 域名
- 请确保配置文件使用 UTF-8 编码保存

## 4. 运行程序

### 4.1 运行步骤
1. 确保所有必要文件都在同一目录下
2. 双击运行 `cursor_pro_keep_alive.exe`
3. 程序会自动执行以下操作：
   - 删除现有账号
   - 注册新账号
   - 更新认证信息

### 4.2 运行提示
- 程序运行过程中会显示各个步骤的执行状态
- 如果出现验证码，程序会自动处理
- 运行完成后会显示操作结果

## 5. 常见问题解决

### 5.1 配置文件错误
错误提示：`配置文件不存在`
- 解决方法：确保 `config.ini` 文件在程序同目录下

### 5.2 插件加载失败
错误提示：`插件不存在`
- 解决方法：确保 `turnstilePatch` 文件夹在程序同目录下
- 注意：即使插件加载失败，程序仍会继续执行

### 5.3 账号注册失败
- 检查邮箱格式是否正确（必须是 mailto.plus）
- 确保密码符合要求
- 检查网络连接是否正常

## 6. 注意事项

1. 运行环境要求：
   - Windows 操作系统
   - 稳定的网络连接

2. 安全提示：
   - 请妥善保管配置文件，避免泄露账号信息
   - 建议定期更改密码

3. 使用建议：
   - 建议在非高峰时段运行程序
   - 保持配置文件的定期备份

## 7. 技术支持

如遇到问题，请检查：
1. 配置文件格式是否正确
2. 必要文件是否完整
3. 网络连接是否正常

## 8. 免责声明

本程序仅供学习和研究使用，请遵守相关服务条款和法律法规。使用本程序产生的任何后果由用户自行承担。