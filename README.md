# PiKVM-PWM-Fan
## A writeup on adding PWM fan control to the Geekworm PiKVM-A3 kit
The Geekworm [PiKVM-A3](https://geekworm.com/products/pikvm-a3) kit includes a 30mm fan integrated into the X630-A3 Hat. The fan is hard-wired to 5V, and runs continuosly at full speed. It's not too noisy, but it's not too quiet either - certainly in my quite office space. So I set out to convert it to a PWM controlled fan that would track the CPU temperature and spin accordingly. The results were very satisfactory. This modification is probably applicable to most any PiKVM clone with a fan, or perhaps even the branded PiKVM devices. I don't have any, so I can't say for sure.

