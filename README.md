# LightKurveCacheAccess

Example 

import LightkurveCacheAccess as lkAcc

mycache = '/home/nielsemb/.lightkurve-cache'

lk_kwargs = {'mission': 'Kepler', 'exptime': 1800, 'author': 'Kepler'}

lcCol = lkAcc.query_lightkurve('KIC7199397', mycache, lk_kwargs)
