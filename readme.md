# Configuration

### TIMEOUT **(float)**

the time in second, when the script considered that port is closed

### IP_LIST **(list)**

list of tuple object. It contains the hostname and ip address.

```python
IP_LIST = [
	#('hostname', A.B.C.D)
	('exemple.com', 8.8.8.8),
	('exemple.com', 8.8.4.4),
	# ...,
]
```


### RAGE_PORT **(list)**

list of tuple object. It contains the min and max of port range

```python
RAGE_PORT = [
	#(20, 25)
	(80, 444),
	# ...,
]
```

### OUTPUT_FILE

It the filename of result scan. The file has prefixed by the date YMD-{{OUTPUT_FILE}}.txt

# usage

```
./ping_p > err.txt
```

err.txt contains every script errors