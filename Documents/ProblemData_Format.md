# 数据格式
## `[Problem_ID].zip`
包含一个文件夹 `[Problem_ID]`。
文件夹内包含输入输出文件：`[id].in/[id].ans`，其中 `id` 为测试点编号（1-base）
SPJ 文件：可执行文件 `spj`，格式参考 `SPJ_Format.md`
Scorer 文件：python 文件 `scorer.py`
配置文件：JSON 文件 `config.json`，为类型 ProblemConfig 的打包
## `[Problem_ID].timestamp`
时间戳，用于与数据服务器同步