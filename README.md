## project_
各类项目汇总

## 文件介绍

每个project文件夹内，包含以下几个部分：

```bash
sample_project
├── data
│   └── raw_data.csv
├── notebooks
│   └── do_something.ipynb
├── projec_introduction.md, etc.
├── project_pre.html 
├── scripts
│   └── do_something.py
├── archive
│   └── previous_versions.ipynb
├── utils
    └── do_something_utils.py
```

*  `projec_introduction.md` 为非notebook形式的项目展示文件，或者项目说明文件（主要用来记录处理数据的时间节点，以及处理的内容和现阶段结果，有点类似于记录**log**）

*  `projec_pre.html` 可能是一个最终版本的展示

* `data/`目录用来存放原始数据，以及处理的中间产物和最终结果。

* `notebooks/` 目录用来存放处理数据的notebook文件

* `scripts/` 和 `utils/` 这两个目录，更多是为未来的任务拓展考虑。参考Medium的文章，Jupyter确实存在局限性。设置`scripts/`目录，是想把Jupyter Notebook以Python脚本文件的形式记录下来，一个完整的脚本文件，是未来写算法的基础。设置`utils/`目录，则是为了记录一些解决问题的脚手架。**看业务需求，这两个目录可以暂时不去创建**

## `.gitignore`文件
