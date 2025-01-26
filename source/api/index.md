---
title: API 接口文档
date: "2025-01-26"
---

## 批量处理音频

> 注意：建议仅在内网环境中调用此接口，或者在外部调用时添加 OSS 上传下载的逻辑层。

**请求 URL:** `http://xxx.xxx.xxx.xxx:8652/handle`

**请求方法:** POST

**请求头：**
```
Content-Type: multipart/form-data
```

**请求参数：**

| 参数名 | 类型 | 说明 |
|--------|------|------|
| files  | File | 要处理的音频文件，支持多文件上传 |
| config | JSON | 处理配置，可从 UI 的"预览配置"处获取 |

![config](assets/config.png)

**示例请求：**

```bash
curl --location --request POST 'http://xxx.xxx.xxx.xxx:8652/handle' \
--header 'User-Agent: Apifox/1.0.0 (https://apifox.com)' \
--form 'files=@"/path/to/your/audiofile.mp3"' \
--form 'config="{}"'
```

**响应：**

接口响应为一个 zip 压缩包，可以点击下载 [多语言字幕](https://github.com/LiberSonora/libersonora.github.io/tree/main/source/assets/test-multilang.zip) 和 [原始字幕](https://github.com/LiberSonora/libersonora.github.io/tree/main/source/assets/test-single.zip) 测试结果

- aaa.mp3
- aaa.srt
- aaaa.lcr
- bbb.mp3
- bbb.srt
- bbb.lcr