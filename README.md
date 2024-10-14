## 简介
**Crypto** 是一款专注于加密货币管理的命令行工具，能够帮助用户生成钱包地址、转换私钥和生成自定义的 TRX 靓号。该工具操作简单高效，适合加密货币的爱好者和开发者使用，支持多系统。

## 关键词
**Crypto** 波场地址生成、TRX靓号生成、Tron地址生成、自定义尾号、离线钱包生成、私钥转换。

## 功能

1. **生成钱包地址及私钥**
   - 使用以下命令生成钱包地址及对应的私钥：
     ```bash
     ./crypto-win.exe t
     ```

2. **私钥转钱包地址**
   - 通过输入私钥生成钱包地址，使用命令：
     ```bash
     ./crypto-win.exe k <私钥>
     ```
   - 示例：
     ```bash
     ./crypto-win.exe k 0541bb4d9d07e56994d5e665f307ef0b7bb4288e29c59399ec111c7e7ab50ada
     ```

3. **助记词转钱包地址**
   - 通过输入助记词生成钱包地址，使用命令：
     ```bash
     ./crypto-win.exe t <助记词>
     ```
   - 示例：
     ```bash
     ./crypto-win.exe t toy,able,spring,scout,wage,choose,shadow,scrub,mesh,essence,fancy,junk
     ```
     或
     ```bash
     ./crypto-win.exe t 'toy,able,spring,scout,wage,choose,shadow,scrub,mesh,essence,fancy,junk'
     ```

4. **TRX 靓号生成（末尾位指定）**
   - 生成指定尾部字符长度为 4 至 12 位的 TRX 钱包地址，使用命令：
     ```bash
     ./crypto-win.exe c <n>
     ```
   - 其中 `n` 为整数，指定尾部的字符长度。

## 安装和使用

1. 根据操作系统选择下载并解压，例如windos就下载 `crypto-win.exe` 文件。
2. 打开命令提示符或终端，进入程序所在的目录。
3. 使用上述命令运行程序并生成所需内容。

## 注意事项

- 请妥善保存私钥和助记词，一旦丢失将无法恢复钱包访问权限。
- 生成靓号地址可能需要一定的时间，具体取决于靓号的复杂度。

## 许可证

该软件遵循 MIT 许可证。
