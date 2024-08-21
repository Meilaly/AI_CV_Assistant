程序说明：
根据【Datawhale AI夏令营第四期】 浪潮源大模型应用开发方向的教程Task04里面的AI简历助手做了代码优化和功能增加：
1.实现了可以阅读ppt，word，txt文件，pdf也可以但是效果不佳。
2.保留了文本输入解析的功能同时增加了基于Streamlit的前端交互可视化界面。
原代码网址：https://datawhaler.feishu.cn/wiki/FWgSwZw4GitsFAk4E3qc05U6nhg
运行方式：
终端输入：streamlit run app.py --server.address 127.0.0.1 --server.port 6006
支持文本输入和上传文件（ppt，word，txt没问题，pdf的效果不稳定）
文本输入多人的话必须标序号，例如：
1.甲，33岁，教师
2.乙，18岁，实习生

不然可能会报错！！！