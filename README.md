aplayer致力于将ffplay进行适当的裁剪和重构，以方便初学者快速理解ffplay的源码，入门ffmpeg。

本工程的源码基于ffmpeg-4.0.2。

裁剪主要是将主流程之外的代码，或是导致理解负担的代码移除。

重构则是将长函数按主流程、主步骤进行拆分，拆分为更容易理解的子函数，降低函数的复杂度。

**注意本工程并不适合工程级别的使用，只作为入门学习用**

# 已完成

## 裁剪

- AVFILTER
- cmd options
- ffplay options
- format options
- codec options
- config.h依赖
- `#if`宏
- 音频可视化代码



## 重构

- 重构main函数
- 重构读线程
- 重构video显示线程
- 重构audio_decode_frame

# 计划中

- 重构各个长函数
- 重构复杂的if条件
- 增加注释

# 不做什么

不迭代新的功能