# 1 start MySQL
	#/etc/init.d/mysql start
# 2 start mongodb
	#/etc/init.d/mongodb start
	modify the config file:
	# vim /etc/mongodb.conf(modify the default listen ip)
		bind_ip = 0.0.0.0
	# restart mongodb
	connection
	# mongo
# 3 start redis
	# /etc/init.d/redis-server start
	modify the default listen ip
	# vim /etc/redis/redis.conf
		bind 0.0.0.0
	restart service
	# /etc/init.d/redis-server restart
