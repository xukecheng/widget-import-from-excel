# 维格小程序 - 从 Excel 导入

可以从 .xlsx .csv .xls 文件追加导入更多数据

## 📄 使用指南

导入的文件需要和被导入的维格表内的列标题一致，示例如下：
![vika_field.png](https://oss.xukecheng.tech/image/png/1646017424.png)
![excel_field.png](https://oss.xukecheng.tech/image/png/1646709258.png)

模板示例：https://vika.cn/share/shrzWKKTvijSdqyE0EAlB/fodFCh1bgBuhe

需要注意的是：
- 不支持导入计算字段，“计算字段”的意思是，不允许用户主动写入值的字段类型。（比如：自增数字、公式、神奇引用、修改时间、创建时间、修改人、创建人）
- 不支持导入附件、成员、神奇关联字段
- 由于 SDK 的限制，单多选暂时不支持导入新选项（PS：导入多选列时，多个选项需要用 "," 符号分隔）
- 导入的文件里如果含有日期字段，格式需要为：YYYY-MM-DD hh:mm:ss 
- 不可在仪表盘使用
## 🎯 更新日志

v0.0.1 - 2021年2月28日：发布首个版本