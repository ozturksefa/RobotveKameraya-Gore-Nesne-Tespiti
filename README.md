# RobotveKameraya-Gore-Nesne-Tespiti

<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.0 Transitional//EN">
<html>
<head>
	<meta http-equiv="content-type" content="text/html; charset=utf-8"/>
	<title></title>
	<meta name="generator" content="LibreOffice 7.0.2.2 (Linux)"/>
	<meta name="created" content="00:00:00"/>
	<meta name="changed" content="00:00:00"/>
	
</head>
<body lang="en-US" link="#000080" vlink="#800000" dir="ltr"><pre>Aşağıda verilen poz bilgilerini verildikleri koordinat sistemlerine dikkat ederek matrislerde saklayınız. 

Robotların ve eşyaların isimlerini de string olarak matrise ekleyiniz. Robotların üzerinde yük olup olmadığı bilgisini rastgele olarak atayınız. 



Numaranızın içindeki tüm rakamları toplayıp beşe göre mod alınız. Örneğin : 1111111111 = 9 % 6 = 3

Şekilde verilen bilgileri kullanarak size tabloda verilen bir hedef için tüm robotların uzaklık bilgilerini bir matriste saklayınız.

Şekilde verilen bilgileri kullanarak size tabloda verilen bir hedef için en yakın robotu bulunuz (yük durumuna bakmadan)..

Şekilde verilen bilgileri kullanarak size tabloda verilen bir hedef için en yakın ve üzerinde yük bulunmayan robotu bulunuz..

Tabloda verilen &quot;Hedef kamera&quot; çerçevesine göre hedef'in poz bilgisini tanımlayınız.



numaranızın rakamları toplamı 

Hedef	Hedef Kamera
0	varil	kinect
1	çöp kutusu	kamera
2	tekerlek	derinlik kamera
 3	 kutu	 kinect
 4	 tuğla	 kamera
 5	geniş tuğla 	 derinlik kamera
 6	 varil	 kinect





Şekilde verilen 

kamera 


kamera
x	y	z	roll	pitch	yaw
-5,538	-8,437	2,549	15	-45	25

derinlik kamera
x	y	z	roll	pitch	yaw
5,949	-2,590	0	45	45	0


kinect kamera
x	y	z	roll	pitch	yaw
-3,800	-3,744	0	0	30	0




kamera'ya göre iris_robot
x	y	z	roll	pitch	yaw
8,150	1,544	-1,479
45	30	0




kamera'ya göre create robot
x	y	z	roll	pitch	yaw
10,623	0,544	-2,719
0	0	0



kamera'ya göre r2 robot
x	y	z	roll	pitch	yaw
10,367	2,412	-1,643
-45	-60	50



kinect kamera'ya göre Husky Robot
x	y	z	roll	pitch	yaw
3,837	-2,234	0,479
0	40	30



kinect kamera'ya göre yourobot
x	y	z	roll	pitch	yaw
4,289	3,189	0,479
30	0	35





kinect kamera'ya göre turtlebot3_waffle

x	y	z	roll	pitch	yaw
2,480	4,849	0,479
0	45	25



derinlik kamera'ya göre pioneer3at

x	y	z	roll	pitch	yaw
6,149	5,281	0,265
20	15	65



derinlik kamera'ya göre pioneer2dx

x	y	z	roll	pitch	yaw
0,948	6,729	0,265
-20	-15	0


derinlik kamera'ya göre mars rover

x	y	z	roll	pitch	yaw
9,378	6,643	1,265
-30	45	-15



dünya koordinat sistemine göre kutu

x	y	z	roll	pitch	yaw
6,954	-7,144	0,149
0	0	0


dünya koordinat sistemine göre tuğla

x	y	z	roll	pitch	yaw
6,954	-7,144	0,149
0	0	0


dünya koordinat sistemine göre geniş tuğla

x	y	z	roll	pitch	yaw
5,618	-9,217	0	0	0	0



dünya koordinat sistemine göre varil

x	y	z	roll	pitch	yaw
0,401	-8,934	0
0	0	0


dünya koordinat sistemine göre çöp kutusu

x	y	z	roll	pitch	yaw
1,458	-2,732	0
0	0	0



dünya koordinat sistemine göre kereste

x	y	z	roll	pitch	yaw
4,435	-0,911	0,04
0	0	0



dünya koordinat sistemine göre tekerlek

x	y	z	roll	pitch	yaw
2,414	-1,050	0,02
0	0	0
</pre>
</body>
</html>
