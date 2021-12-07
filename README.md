### 任务
请分析项目中的csv 数据
方向可以自定（例子: 催回效果，催收工作量，分布情况）

#### 背景 
这个是一些金融贷款的催收数据

#### 主要字段解析：
id,
collect_case_id(分配的caseid), 
can_recall_time(可以再次拨打的时间点),
collect_amount(催回金额)，
repaid_amount(客户还款金额)，
remark(催收员的编写的备注。西班牙文), 
repaid_time(还款时间)， 
collector_id(催收员id)，
collection_time(催收员工作的)，
contact_relation（联系的是谁（类别）），
contact_status(联系状态)， 
repay_willingness(还款意愿)


要求：使用任意你熟悉的工具做分析,提交你的分析代码(python/sql/r/excel)、分析结果。
注意：这是一份有随机成分的数据。请暂时忽略其中西班牙文显示的重音符号