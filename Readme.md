Collect the tips of linux kernel development

## Example1
The simplest kernel module demo

## Example2
Enhance Example0, append module infomation, parameter 
Parameter Passing: insmod example.ko debug_enable=1 dispstr="World"
Dyanamicly change the parameter via sysfs
List Module Info: modinfo brook.ko

## Example3
DebugFS Example
Dynamicly change the variable via debugfs
Need to mount debugfs
