# aippt

大模型生成PPT

## usage

阿里云百炼平台，创建72B通义模型，将鉴权配置导出如下环境变量：

```
export AGENT_KEY=''
export APP_ID=''
export ACCESS_KEY_ID=''
export ACCESS_KEY_SECRET=''
```

启动程序

```
python aippt.py
```

执行过程

```
输入主题:python语法入门
输入页数:8
总共8页...
生成第1页:第一页：Python简介
生成第2页:第二页：Python安装与环境设置
生成第3页:第三页：Python基础语法
生成第4页:第四页：流程控制
生成第5页:第五页：函数与模块
生成第6页:第六页：列表与切片
生成第7页:第七页：字典与集合
生成第8页:第八页：异常处理
```

产出结果

```
python语法入门.pptx
```