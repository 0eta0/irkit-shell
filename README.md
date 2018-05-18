This is shell script to get "clienttoken" "clientkey" "deviceid" automatically.

## USEAGE of IRKit-autoget
Command
`irkit-autoget <IP ADDRESS>`

You can get <IP ADDRESS> to use Bonjour.

First,
`dns-sd -B _irkit._tcp`
You can see irkit bonjour hostname. 
(Maybe it is irkit****.local)

Second,
`dns-sd -G v4 irkit****.local`
Then, you can get <IP ADDRESS>.

## USEAGE of IRKit
You have to replace IRKit****.local to your IRKit bonjour hostname before you use this command.

### -get
get newest infrared signal from irkit.

### -send
send infrared signal of second argument to irkit.

### -help
display useage of this command.
