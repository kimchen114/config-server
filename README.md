# config-server
配置中心

#客户端要实现动态刷新配置需要做一下操作
##1.加入jar包
		<dependency>
			<groupId>org.springframework.boot</groupId>
			<artifactId>spring-boot-starter-actuator</artifactId>
		</dependency>
##2.在主类上添加@RefreshScope注解
##3.用户需要有ROLE_ACTUATOR角色
##4.localhost:8763/refresh		 post请求 调取接口

