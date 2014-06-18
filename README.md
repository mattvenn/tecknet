#Battery

battery is a samsung [icr18650-30a](http://www.fasttech.com/product/1314901-authentic-samsung-icr18650-30a-18650-4-35v)

#Similiar battery review

[Samsumg 2800](http://www.torchythebatteryboy.com/p/18650-batteries-chargers.html)

#Low voltage of Li-Ion

[3v on the candle power forums](http://www.candlepowerforums.com/vb/showthread.php?212790-Li-ion-Reasonable-low-voltage-cutoff)
[3.2v from wikipedia](http://en.wikipedia.org/wiki/Cutoff_voltage)

#Rasp model b current test

* desolder battery from circuit
* measure current drawn when powering model b (no peripherals)

result = 0.5A

#DC load test

* battery is out of circuit with charger
* set low voltage to 3v, current to 0.5A
* run time test.

# Charge current

* from flat (3v) 0.6A
* dropping to 0.4A when batt is at 4v
* 0.2A at 4.15v

# Cutoff voltage

regulates to 5v (with load connected) down to 2.5v then cuts off.
2.5v seems low for a Li-Ion.

#Todo

measure voltage curve on samsung


