# SM4
### 已完成 
在最简单的ECB模式下，无填充
input 128bit 待解密/加密数据，output 128bit 加密/解密数据
- sm4_F: X iteration
- sm4_round key: 密钥扩展

1.32轮求得所有密钥

2.根据mode选择密钥使用方式进行加密解密

3.每个时钟周期迭代一次，需要65个时钟周期

### 未完成
- 串口传输
- 密钥存储
- 流水线方式
- ECB、CBC、CTR等模式
- pkcs7等填充方式
