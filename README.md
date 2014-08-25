【需求分析】
1、学区房基本划片信息
2、使用baidu maps API实现图形化显示
3、追踪最新成交报告
4、学区房打分机制
5、户口迁入、成交注意事项

【数据表格设计】
tbl_school{
	VAR name,
	VAR poly_json //多边形数据
	VAR 

}

tbl_house{
	INT price,
	VAR url,
	int score
}

【技术细节】
LAMP架构，使用php简单实现，框架选用yii

美工实现选用bootstrap
数据表现选用d3project

update:2014/8/25/23:00
