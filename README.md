# 中文大模型能力评测榜单（持续更新）
- 目前已囊括11个大模型，覆盖百度文心一言、chatgpt、阿里通义千问、讯飞星火等商用模型，以及belle、chatglm6b 等开源大模型。
- 支持多维度能力评测，包括分类能力、信息抽取能力、阅读理解能力。
- 不仅提供能力评分排行榜，也提供所有模型的原始输出结果！

## 🔄 最近更新
- [2023/6/4] 发布v1版本评测榜单

## 📊 排行榜
### 综合能力排行榜
综合能力得分为分类能力、信息抽取能力、阅读理解能力三者得分的平均值。
![lin](pic/total.png)

| 类别	 | 大模型	                    | 总分	    | 排名  |
|-----|-------------------------|--------|-----|
| 商用	 | chatgpt-3.5	            | 93.8	  | 1   |
| 开源	 | belle-llama-13b-2m	     | 79.2	  | 2   |
| 商用	 | chatglm官方               | 76.9	  | 3   |
| 商用	 | 讯飞星火	                   | 76.6	  | 4   |
| 开源	 | belle-llama-13b-ext	    | 71.9	  | 5   |
| 开源	 | BELLE-on-Open-Datasets	 | 70.9	  | 6   |
| 开源	 | belle-llama-7b-2m	      | 70.4	  | 7   |
| 开源	 | Ziya-LLaMA-13B-v1	      | 70.2   | 	8  |
| 开源	 | chatglm-6b              | 	66.1	 | 9   |
| 商用	 | 文心一言                    | 60.6   | 	10 |
| 商用	 | 阿里通义千问                  | 	49.4  | 	11 |

<br><br>
### 分类能力排行榜
![lin](pic/classification.jpg)

| 类别	 | 大模型	                   | 分类能力	 | 排名 |
|-----|------------------------|-------|----|
| 商用	 | chatgpt-3.5	           | 98	   | 1  |
| 商用	 | chatglm官方	             | 82	   | 2  |
| 开源	 | BELLE-on-Open-Datasets | 82	   | 3  |
| 开源	 | belle-llama-13b-2m	    | 82	   | 4  |
| 开源	 | belle-llama-7b-2m	     | 76	   | 5  |
| 开源	 | belle-llama-13b-ext    | 74	   | 6  |
| 开源	 | Ziya-LLaMA-13B-v1	     | 72	   | 7  |
| 商用	 | 讯飞星火	                  | 70	   | 8  |
| 开源	 | chatglm-6b	            | 66	   | 9  |
| 商用	 | 文心一言	                  | 48	   | 10 |
| 商用	 | 阿里通义千问	                | 44	   | 11 |

<br><br>
### 信息抽取能力排行榜
![lin](pic/extract.png)

| 类别	 | 大模型	                    | 信息抽取能力	 | 排名 |
|-----|-------------------------|---------|----|
| 商用	 | chatgpt-3.5	            | 88	     | 1  |
| 商用	 | 讯飞星火	                   | 79	     | 2  |
| 商用	 | chatglm官方	              | 76	     | 3  |
| 开源	 | belle-llama-13b-2m	     | 75	     | 4  |
| 商用	 | 文心一言	                   | 71	     | 5  |
| 开源	 | chatglm-6b	             | 69	     | 6  |
| 开源	 | belle-llama-13b-ext	    | 65	     | 7  |
| 开源	 | belle-llama-7b-2m	      | 64	     | 8  |
| 开源	 | BELLE-on-Open-Datasets	 | 62	     | 9  |
| 开源	 | Ziya-LLaMA-13B-v1	      | 62	     | 10 |
| 商用	 | 阿里通义千问	                 | 47	     | 11 |

<br><br>
### 阅读理解能力排行榜
![lin](pic/mrc.png)

| 类别	 | 大模型	                    | 阅读理解能力	 | 排名 |
|-----|-------------------------|---------|----|
| 商用	 | chatgpt-3.5	            | 95.3	   | 1  |
| 商用	 | 讯飞星火	                   | 80.7	   | 2  |
| 开源	 | belle-llama-13b-2m	     | 80.7	   | 3  |
| 开源	 | belle-llama-13b-ext	    | 76.7	   | 4  |
| 开源	 | Ziya-LLaMA-13B-v1	      | 76.7	   | 5  |
| 商用	 | chatglm官方	              | 72.7	   | 6  |
| 开源	 | belle-llama-7b-2m	      | 71.3	   | 7  |
| 开源	 | BELLE-on-Open-Datasets	 | 68.7	   | 8  |
| 开源	 | chatglm-6b	             | 63.3	   | 9  |
| 商用	 | 文心一言	                   | 62.7	   | 10 |
| 商用	 | 阿里通义千问	                 | 57.3	   | 11 |

<br><br>
## 各项能力评分
| 类别 | 大模型                    | 分类能力 | 信息抽取能力 | 阅读理解能力 | 综合能力 |
|----|------------------------|------|--------|--------|------|
| 商用 | chatgpt-3.5            | 98   | 88     | 95.3   | 93.8 |
| 商用 | 文心一言                   | 48   | 71     | 62.7   | 60.3 |
| 商用 | chatglm官方              | 82   | 76     | 72.7   | 76.9 |
| 商用 | 讯飞星火                   | 70   | 79     | 80.7   | 76.6 |
| 商用 | 阿里通义千问                 | 44   | 47     | 57.3   | 49.4 |
| 开源 | chatglm-6b             | 66   | 69     | 63.3   | 66.1 |
| 开源 | belle-llama-7b-2m      | 76   | 64     | 71.3   | 70.4 |
| 开源 | BELLE-on-Open-Datasets | 82   | 62     | 68.7   | 70.9 |
| 开源 | belle-llama-13b-2m     | 82   | 75     | 80.7   | 79.2 |
| 开源 | belle-llama-13b-ext    | 74   | 65     | 76.7   | 71.9 |
| 开源 | Ziya-LLaMA-13B-v1      | 72   | 62     | 76.7   | 70.2 |

<br><br>
## 原始评测数据
见本项目的[eval文件目录](eval)