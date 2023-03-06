# MeinaMix

## 简介

可以在关键词很少的情况下输出好看的图片，且手的生成也很不错

### 模型链接

https://civitai.com/models/7240/meinamix

### 作者主页

https://civitai.com/user/Meina

## 关键词

暂无

## 推荐参数

### 正向prompt

### 负向prompt
```
(worst quality, low quality:1.4), monochrome, zombie
```
### 其他参数

<!-- tabs:start -->

### **1**

| Key        | Value               | remarks          |
|------------|---------------------|------------------|
| samplers   | Euler A             |                  |
| steps      | 30+                 |                  |
| CFG        | 5-9                 |                  |
| Clip skip  | 2                   |                  |
| Hires. fix | R-ESRGAN 4x or NONE |                  |
| fix steps  | 10~20               |                  |
| denoising  | 0.1-0.6             | 数值较高可能导致手部细节出现问题 |

### **2**

| Key        | Value               | remarks          |
|------------|---------------------|------------------|
| samplers   | DDIM                |                  |
| steps      | 20-50               |                  |
| CFG        | 5-9                 |                  |
| Clip skip  | 2                   |                  |
| Hires. fix | R-ESRGAN 4x or NONE |                  |
| fix steps  | 10~20               |                  |
| denoising  | 0.1-0.6             | 数值较高可能导致手部细节出现问题 |

<!-- tabs:end -->

## 佳品展示