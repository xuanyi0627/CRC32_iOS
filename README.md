#CRC32_iOS

>###CRC32位校验在iOS中的使用方法


###简单介绍：使用方法

```
NSData *sendData = [[NSData alloc] init];  
int32_t checksum = [sendData crc32];
```

###具体使用方式：见源码Demo

