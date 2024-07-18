# Volatility

```
python2 vol.py --info
```

## Enumerate Processes
```
python2 vol.py --profile=Win7SP1x64 -f MemoryDump_Lab1.raw pslist
python2 vol.py --profile=Win7SP1x64 -f MemoryDump_Lab1.raw pstree
python2 vol.py --profile=Win7SP1x64 -f MemoryDump_Lab1.raw pscan
```

## Command Lines
```
python2 vol.py --profile=Win7SP1x64 -f MemoryDump_Lab1.raw cmdline
```

## Envrionmental Variables
```
python2 vol.py --profile=PROFILE envars -f file.dmp [--pid <pid>]
python2 vol.py --profile=PROFILE -f file.dmp linux_psenv [-p <pid>] #Get env of process. runlevel var means the runlevel where the proc is initated 
```

## File Extract


