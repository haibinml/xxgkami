# 🎫 小小怪卡密验证系统

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg?cacheSeconds=2592000)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![PHP Version](https://img.shields.io/badge/PHP-7.0+-green.svg)
![MySQL](https://img.shields.io/badge/MySQL-5.7+-orange.svg)

</div>

一个功能强大、界面美观的卡密验证系统，支持多种验证方式，提供完整的API接口，适用于软件授权、会员验证等场景。采用现代化的UI设计，响应式布局，支持移动端访问。

## ✨ 系统预览

![da68d84d438794beebb6af2a22a156e9.png](https://www.helloimg.com/i/2025/01/07/677cb25d6da53.png)

## 🌟 主要特点

### 🛡️ 安全可靠
- 采用先进的加密技术，确保卡密数据安全
- 防暴力破解机制，自动封禁异常IP
- 完善的安全性验证，多重安全校验
- 支持数据加密存储，保护敏感信息
- SSL安全连接支持

### 🔌 API支持
- RESTful API接口，标准化接口设计
- 支持POST/GET验证方式
- 详细的接口文档，简单易用
- 支持多种验证场景
- API调用频率限制
- 接口调用统计

### ⚡ 高效稳定
- 快速的响应速度，毫秒级验证
- 稳定的运行性能，7x24小时运行
- 经过性能优化，支持大规模验证
- 支持高并发访问
- 服务器资源占用低

### 📊 数据统计
- 实时统计功能，数据一目了然
- 详细的数据分析，助力决策
- 直观的图表展示，多种图表类型
- 完整的使用记录，可追溯管理
- 导出报表功能

## 🚀 功能特性

### 💳 卡密管理
- 批量生成卡密，支持自定义前缀
- 自定义卡密有效期，灵活设置
- 支持永久和限时卡密
- 卡密状态实时监控
- 支持导出Excel
- 批量导入功能
- 卡密使用记录
- 支持删除和禁用

### ✅ 验证功能
- 在线Web验证，界面美观
- API接口验证，支持多种框架
- 支持多种验证方式
- 验证结果实时反馈
- 异常验证提醒
- IP限制功能

### ⚙️ 系统设置
- 网站基础信息配置
- 安全设置，IP白名单
- 联系方式管理
- 系统特点自定义
- 轮播图管理
- 欢迎提示设置
- 邮件通知配置
- 系统日志记录

### 📈 数据统计
- 使用趋势分析
- 卡密使用统计
- 实时数据展示
- 图表可视化
- 导出报表
- API调用统计
- 用户行为分析

## 💻 技术栈

### 前端
- HTML5、CSS3、JavaScript
- Font Awesome 6.0
- Chart.js 图表库
- 响应式设计
- 现代化UI界面

### 后端
- PHP 7.0+
- MySQL 5.7+
- PDO数据库操作
- RESTful API设计
- 缓存机制

### 服务器
- Apache/Nginx
- SSL证书支持
- 伪静态规则
- 性能优化

## 🔧 安装说明

### 环境要求
- PHP 7.0或更高版本
- MySQL 5.7或更高版本
- Apache/Nginx服务器
- PDO PHP扩展
- GD PHP扩展
- OpenSSL PHP扩展

### 安装步骤
```bash
# 1. 下载源码
git clone https://github.com/xiaoxiaoguai-yyds/card-auth-system.git

# 2. 设置目录权限
chmod -R 755 card-auth-system
chmod -R 777 card-auth-system/upload

# 3. 配置虚拟主机
# 4. 访问安装页面
http://your-domain/install/
```

### 安装配置
1. 配置数据库连接信息
2. 设置管理员账号
3. 初始化系统设置
4. 完成安装

## 📝 使用说明

### 👨‍💼 管理员后台
1. 访问 `http://your-domain/admin.php`
2. 使用安装时设置的管理员账号登录
3. 进入管理面板

### 🔑 API调用
```php
// POST方式调用示例
$url = "http://your-domain/api/verify.php";
$data = [
    "card_key" => "您的卡密",
    "api_key" => "您的API密钥"
];
$result = curl_post($url, $data);
```

## 🔐 安全建议

1. 🗑️ 安装完成后删除install目录
2. 🔒 定期修改管理员密码
3. 💪 使用强密码策略
4. 💾 定期备份数据
5. 🔄 及时更新系统
6. 🛡️ 配置防火墙规则
7. 📝 开启系统日志
8. 🔍 定期检查异常记录

## 📅 更新计划

- [ ] 多语言支持
- [ ] 微信支付接口
- [ ] 支付宝支付接口
- [ ] 手机号验证
- [ ] 邮箱验证码
- [ ] 批量导入功能
- [ ] 自定义主题
- [ ] Docker部署支持

## 🤝 贡献指南

1. Fork 本仓库
2. 创建新分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 提交 Pull Request

## 📄 开源协议

本项目采用 MIT 协议开源，详见 [LICENSE](LICENSE) 文件。

## 👥 联系方式

- 👨‍💻 作者：[xiaoxiaoguai-yyds]
- 📧 邮箱：[2456993017@qq.com]
- 💬 QQ：[2456993017]
- 🌐 网站：[https://www.xxg-yyds.com]

## ⭐ 特别鸣谢

感谢以下开源项目：
- Font Awesome
- Chart.js
- Bootstrap
- jQuery

## 📊 项目统计

![Stars](https://img.shields.io/github/stars/xiaoxiaoguai-yyds/xxgkami/card-auth-system?style=social)
![Forks](https://img.shields.io/github/forks/xiaoxiaoguai-yyds/xxgkami/card-auth-system?style=social)
![Issues](https://img.shields.io/github/issues/xiaoxiaoguai-yyds/xxgkami/card-auth-system)
![Pull Requests](https://img.shields.io/github/issues-pr/xiaoxiaoguai-yyds/xxgkami/card-auth-system)

---

如果觉得这个项目对你有帮助，欢迎 Star ⭐️ 支持一下！ 
