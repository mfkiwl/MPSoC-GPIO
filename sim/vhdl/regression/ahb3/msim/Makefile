all: build

build:
	@if [ ! -e work ]; then vlib work; fi
	@vcom -2008 -f system.vc
	vsim -c -do run.do work.mpsoc_gpio_testbench
