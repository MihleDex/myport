# myport
Simple python port tcp scanner that can be imported

## Usage
import myport

sc = myport.Scanner(target,port_range_start,port_range_end,timeout)

sc.scan() #This will print current open ports

print(sc.open_ports) #This will print a list of all open ports
