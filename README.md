# LightKurveCacheAccess

Example 

import LightkurveCacheAccess as lkAcc

mycache = '/home/nielsemb/.lightkurve-cache'

use_cached = True

lk_kwargs = {'mission': 'Kepler', 'cadence': 'short'}
                                                                                    
lc = lkAcc.query_lightkurve('KIC7199397', mycachce, use_cached, lk_kwargs)
