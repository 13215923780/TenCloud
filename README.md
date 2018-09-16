# TenCloud
拾云是为企业级分布式云应用提供支撑的云计算PaaS平台，集成了一系列前沿云技术和企业管理方法。

# 管理
* 需求文档：https://workflowy.com/
* 设计文件：蓝湖 - https://lanhuapp.com
* 原型设计：
	* 墨刀 - https://pro.modao.cc/ （设计使用）  + 
	* AXure - 产品提供一些建议性页面参考  
* 任务跟踪：<br>
	* 产品计划 - workflowy的todoList
	* 实际跟踪 - https://tower.im 
        

# 技术
  * 服务端
	* 短信通道：sendcloud
	* 异常上报：腾讯Bugly
	* 框架
		* 负载均衡：nginx
		* 处理请求:  tornado
		* 进程管理:  supervisor
		* 数据存储:  mysql
		* 缓存系统:  redis
		* 容器技术:  docker
		* 容器编排:  k8s
		* 接口风格:  restful
        
   
  * 安卓
	* 整体采用MVP模式，功能模块划分更加清晰，方便应对需求变更
	* 网络层:Retrofit+okHttp3+Gson
	* RxJava
	* 图片:Glide
	* 日志打印:KLog
	* 权限注解:PermissionsDispatcher
	* 内存检测:LeakCanary
	* 图表库:MPAndroidChart
	* 数据库:ObjectBox

  * Web
	* Vue.js
    
