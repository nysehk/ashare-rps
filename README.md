# A股基于欧奈尔 RPS 量化选股

## 1. 运行 `prps--all.py` 文件
运行 `prps--all.py` 文件以启动量化选股程序。



## 2. 运行设置
在运行程序之前，可以根据需求进行以下设置：

### 市场选择
- 默认 `market = 0`：
  - `0`：全部市场
  - `1`：创业板（CYB）
  - `2`：中证 500（ZZ500）
  - `3`：国证 2000（GZ2000）
  - `4`：沪深 300（HS300）
  - `5`：中证 1000（ZZ1000）

### 天数
- 默认 `day = 130`：计算 RPS 的天数为 130 天。

### 日期
- 默认 `today = time.strftime("%Y-%m-%d")`：使用当天时间。
- 可以手动设置回测时间，例如：`today = '2024-12-17'`。


## 3. 输出结果
程序运行后，会根据 RPS 筛选结果输出选股列表。
![image](https://github.com/user-attachments/assets/834091bc-8f5c-4c08-887d-4a69937f0cc4)
op:操作分为买入、卖出、持仓、空仓；keep:当前操作的持续天数；
分为rps 120/60/20/5天，rps值越高，股票/板块越强；




## 4. 对接飞书机器人
将筛选结果通过飞书机器人发送。
<img width="161" alt="image" src="https://github.com/user-attachments/assets/c5c63a56-910d-4ae0-ba68-3212571903c7" />



## 使用步骤
1. 运行 `prps--all.py` 文件。
2. 根据需求设置市场、天数和日期。
3. 查看 RPS 筛选结果。
4. 将结果对接飞书机器人。



## 注意事项
- 确保 Python 环境已安装所需依赖。
- 日期格式必须为 `YYYY-MM-DD`。
- 飞书机器人需要提前配置并获取 ID。



## 联系方式
扫描下方二维码，关注微信公众号，获取更多量化投资资讯和工具：

<img width="129" alt="image" src="https://github.com/user-attachments/assets/b4cadf73-a7ca-4116-8614-337d9d7b07d4" />



