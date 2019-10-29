# My-web-resume
自己的网页版简历
<strong>下面是详细的页面展示（每个页面还有各个功能）</strong></br></br>
		<strong>一、车辆管理：</strong>(包括登入，注册，删除)</br></br>
		<strong>1、车辆登入:</strong></br>
		服务协议为HTTP REST或MQTT之间按MEC实施需求选一种。服务支持参数包括：</br>
vin： 车vin号（必须提供）</br>
validState: 车辆状态（必须提供）</br>
expireTimestamp：失效时间（必须提供）</br>
如果vin未注册或已登入，则报错。如果expireTimestamp已过期，则报错。</br></br>
<strong>2、车辆注册:</strong></br>
		服务协议为HTTP REST。服务支持参数包括：</br>
vin： 车vin号（必须提供）</br>
carType：车型（必须提供）</br>
carType：车型（必须提供）</br>
carPriority：车辆优先级(必须提供，用于后续发生轨迹冲突时进行优化条件)</br>
车型的3D建模、宽度、长度等信息通过手工完成。如果vin已注册、或carType不存在，则报错。</br></br>
<strong>3、车辆删除:</strong></br>
		服务协议为HTTP REST。服务支持参数包括：</br>
vin： 车vin号（必须提供）</br>
如果vin未注册，则报错。</br></br>
			![image](https://github.com/xiaola66/TSP-/blob/master/img/vehicle.png)</br></br>
			![image](https://github.com/xiaola66/TSP-/blob/master/img/vlogin.png)</br></br>
			![image](https://github.com/xiaola66/TSP-/blob/master/img/vdelenter.png)</br></br></br>
