# Volatility

## Installation
For vol2
```
git clone https://github.com/volatilityfoundation/volatility.git
cd volatility
sudo python2 setup.py install
pip2 install pycryptodome
pip2 install distorm3==3.3.4
```

```
python2 vol.py --info
```

## Information about the Memory Dump
```
python2 vol.py -f file.dmp imageinfo
python2 vol.py -f file.dmp kdbgscan
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


