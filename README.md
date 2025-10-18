# Neptune Prover 挖矿程序

这个仓库用于托管 DR Neptune Prover 挖矿程序的二进制文件。

## 📦 版本信息

- **版本**: v3.2.1
- **系统**: Ubuntu 20.04
- **文件**: ubuntu_20-dr_neptune_prover-3.2.1.tar.gz
- **大小**: ~40MB (压缩后)

## 🚀 快速开始

### 下载

```bash
# 直连下载
wget https://github.com/Klinola/neptune/releases/download/v3.2.1/ubuntu_20-dr_neptune_prover-3.2.1.tar.gz

# 或使用代理加速（国内服务器）
wget https://ghproxy.cc/https://github.com/Klinola/neptune/releases/download/v3.2.1/ubuntu_20-dr_neptune_prover-3.2.1.tar.gz
```

### 安装

```bash
# 解压
tar -xzf ubuntu_20-dr_neptune_prover-3.2.1.tar.gz
cd dr_neptune_prover

# 赋予执行权限
chmod +x dr_neptune_prover
```

### 运行

```bash
./dr_neptune_prover -w YOUR_ACCOUNT.worker_name -p stratum+tcp://neptune.drpool.io:30127
```

**参数说明**：
- `-w`: Worker 名称，格式为 `账户名.矿机名`
- `-p`: 矿池地址和端口

## 📋 系统要求

- Ubuntu 20.04 或更高版本
- x86_64 架构
- 至少 4GB 内存
- 至少 1GB 磁盘空间

## 🔗 相关链接

- **矿池官网**: [Neptune Pool](https://neptune.drpool.io)
- **原始下载**: https://pub-e1b06c9c8c3f481d81fa9619f12d0674.r2.dev/image/v2/ubuntu_20-dr_neptune_prover-3.2.1.tar.gz

## 📝 更新日志

### v3.2.1
- 初始版本发布
- 支持 Ubuntu 20.04

## ⚠️ 注意事项

1. 请确保您的系统满足运行要求
2. 建议使用 screen 或 tmux 在后台运行
3. 定期检查日志确保正常运行

## 📞 支持

如有问题，请在 Issues 中提出。

---

**免责声明**: 本仓库仅用于存储和分发二进制文件，方便下载。原始文件版权归原作者所有。

