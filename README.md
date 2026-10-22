# Dissertation · 论文复现材料

博士论文的数据与代码附录归档，按章节提供实验材料。此仓库用于阅读、研究与复现，不是可直接启动的应用。

## 内容

- `Xiujia dissertation manuscript .zip`：论文文稿归档。
- `chapter3.zip`、`chapter4.zip`、`chapter5.zip`：对应章节的代码与实验材料。
- `twitter15_twitter16.zip`：Twitter15/Twitter16 相关数据归档。

## 使用方法

```bash
git clone https://github.com/yxjsxy/dissertation.git
cd dissertation
```

按论文中对应章节选择压缩包，解压到独立目录，先阅读包内的说明和代码依赖，再运行实验。章节包并非同一个 Python 项目，仓库根目录没有统一安装、训练或评估命令。

## 复现注意事项

记录所用章节、数据划分、参数、随机种子和环境版本。历史实验依赖可能与当前 Python/机器学习框架不兼容，不要假设解压后可直接使用最新版依赖。数据使用与再分发需遵守原始数据来源的条件；本 README 不额外授予数据许可。
