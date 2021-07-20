# pynetlog

```
pip3 install pynetlogo seaborn
python3 -m pip install jpype1
python3 -m pip install jupyterlab
jupyter lab
```

Put the script in as
```
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
sns.set_style('white')
sns.set_context('talk')
import pyNetLogo

netlogo = pyNetLogo.NetLogoLink(gui=True, netlogo_home= "/home/bai/netlogo", netlogo_version="6.2")
```
