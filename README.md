# GYMCU680
GY-MCU680 (BME680 sensor with STM32 mcu module) serial data decode example in Golang

- Note: IAQ value will be usable after module power on 5 minutes

## Install
go get golang.org/x/sys/unix  
go get github.com/tarm/serial

## Run
go run main.go /dev/ttyUSB0
