车牌识别Demo
========
车牌识别Demo

用FFmpeg打开视频，并获取图像真图片进行车牌识别
CxImage处理图片


输出结果图片的命名为： 日期_时间_车牌_号牌种类_车牌颜色_车辆速度.bmp
1)号牌种类 参考GA24.7（如01-大型汽车，02-小型汽车，25-农机号牌，41-无号牌，42-假号牌，99-其他号牌），不能为空；
2)号牌颜色	0-白色，1-黄色，2-蓝色，3-黑色，4-绿色，9-其它颜色，不能为空
3)车辆速度 最长3位，单位：公里/小时
如:	 \
	2014-02-24_15.29.24 京W56Y2 小型汽车  黑色 0 \
	2014-02-24_15.29.24_京W56Y22_02_3_0.bmp
	2014-02-24_15.29.24_京W56Y22_02_3_0.bmp_plate.bmp
	


