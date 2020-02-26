# Device logs
## Purpose
The sole purpose of this repository is to provide a place where device support can be ensured.
As this is not an offically sanctioned project, we do not have access to every single Intel wireless card, and
as a result, we have to rely on crowdsourcing. 

If you have a compatible Intel wireless card, and can provide logs,
please create an issue with your log file (attached as an attachment), and state the card name.


## How to get logs
```
log show --last boot --predicate 'process == "kernel"' | grep -i intel > ~/Desktop/log.txt
```
Running the above command in Terminal will create a `log.txt` file on your desktop.
