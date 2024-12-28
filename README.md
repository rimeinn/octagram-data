# Octagram 模型数据寄存

此仓库整合寄存一部分 Octagram 模型。

⚠️ 使用 Git LFS。

## 模型列表

所有成品均保存在 `models` 目录下。

- **essay** [八股文模型](https://github.com/lotem/rime-octagram-data), LGPL
  + 作者 @lotem
- **s1** [S1 模型](https://github.com/lotem/rime-octagram-data-s1), LGPL
  + 作者 @be5invis
  + 基于 S1 论坛语料
- **fcitx** [Fcitx 模型](https://github.com/fcitx/libime/blob/master/data/CMakeLists.txt), LGPL
  + 作者 @csslayer
  + 转换自 Fcitx 模型，原语料量达 200G
- **huayu** [华宇模型](https://github.com/linhuman/liblunispim/blob/master/data/lunispim/wordlib/bigram.dat), LGPL
  + 模型来自华宇输入法
  + 转换程序来自 [rime-pure](https://github.com/SivanLaai/rime-pure) 项目和 @warm-ice0x00
  + （目前仅收录繁体模型，简体模型尚待补充）

## 文件名格式

- hant 为繁体字，hans 为简体字
- bg 表示 bigram，tg 表示 trigram
- c 表示字级，w 表示词级

一般来说，拼音类方案建议使用词级模型。

## 注意事项

- 要发挥最佳功效，需要设定合适的参数。
- 繁体词库需使用繁体模型，即使开启繁转简也如此。
