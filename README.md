# NanoVideoManager
自用视频处理小程序.  
运行 NanoVideoManager.py  
制作于 2024 09 27

## Video Merger:
- 将文件夹中按默认顺序合并.
- 默认为不重新编码

## Thumbnails Generator:
- 生成单个或多个视频的缩略图.
- 缩略图生成机制: 从视频中选取变化较大的 20 帧并输出.

## Format Transformer:
- 改变视频格式, 可选择是否重新编码

## Video Spilter:
- 按大小分割视频, 算法问题非常不精确, 实际分割的视频大小在目标值 +- 12.5% 左右. 建议目标值比原目标值减少 12.5%.
- 算法 目标值(MB) / (视频码率(b) + 音频码率(b)) / 8