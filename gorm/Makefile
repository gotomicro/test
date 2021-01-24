APP_PATH:=$(shell dirname $(realpath $(lastword $(MAKEFILE_LIST))))

maxIdleConns1:export EGO_DEBUG=true
maxIdleConns1:
	@cd $(APP_PATH)/concurrentBiggerThanMaxIdleConns1 && go run main.go


maxIdleConns20:export EGO_DEBUG=true
maxIdleConns20:
	@cd $(APP_PATH)/concurrentBiggerThanMaxIdleConns20 && go run main.go


maxIdleConns1Wireshark:export EGO_DEBUG=true
maxIdleConns1Wireshark:
	@cd $(APP_PATH)/concurrentBiggerThanMaxIdleConns1Wireshark && go run main.go
