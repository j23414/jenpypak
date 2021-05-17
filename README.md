# jenpypak

Review of creating a python package

## Install from Github

```
conda create -n test
conda activate test
conda install git pip
pip install git+git://github.com/j23414/jenpypak@main

Collecting git+git://github.com/j23414/jenpypak@main
  Cloning git://github.com/j23414/jenpypak (to revision main) to /private/var/folders/wt/gw5b79wn4sjcpny6d0x4p1680000gn/T/pip-req-build-ogobvg78
  Running command git clone -q git://github.com/j23414/jenpypak /private/var/folders/wt/gw5b79wn4sjcpny6d0x4p1680000gn/T/pip-req-build-ogobvg78
Collecting numpy
  Downloading numpy-1.20.3-cp38-cp38-macosx_10_9_x86_64.whl (16.0 MB)
     |████████████████████████████████| 16.0 MB 14.6 MB/s 
Collecting pandas
  Downloading pandas-1.2.4-cp38-cp38-macosx_10_9_x86_64.whl (10.5 MB)
     |████████████████████████████████| 10.5 MB 3.6 MB/s 
Collecting pytz>=2017.3
  Downloading pytz-2021.1-py2.py3-none-any.whl (510 kB)
     |████████████████████████████████| 510 kB 7.1 MB/s 
Collecting python-dateutil>=2.7.3
  Downloading python_dateutil-2.8.1-py2.py3-none-any.whl (227 kB)
     |████████████████████████████████| 227 kB 5.5 MB/s 
Collecting six>=1.5
  Downloading six-1.16.0-py2.py3-none-any.whl (11 kB)
Building wheels for collected packages: jenpypak
  Building wheel for jenpypak (setup.py) ... done
  Created wheel for jenpypak: filename=jenpypak-0.1.0-py3-none-any.whl size=2411 sha256=18cd1da577fa851a42886140004071d2d3e98827c9f91ba047066d0a72b3cfb4
  Stored in directory: /private/var/folders/wt/gw5b79wn4sjcpny6d0x4p1680000gn/T/pip-ephem-wheel-cache-vee1tjbq/wheels/4d/ee/cc/9785a6cf8d86d773e28d60fb795cd0ce7b8c29659c59d87b11
Successfully built jenpypak
Installing collected packages: six, pytz, python-dateutil, numpy, pandas, jenpypak
Successfully installed jenpypak-0.1.0 numpy-1.20.3 pandas-1.2.4 python-dateutil-2.8.1 pytz-2021.1 six-1.16.0
```
