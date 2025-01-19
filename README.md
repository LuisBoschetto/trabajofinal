# trabajofinal
# Desarrollo trabajo final de carrera

import sys

if sys.version_info.major == 3:
    print('OK')
elif sys.version_info.major == 2:
    print('ERROR: están usando python 2, deberían usar 3')
else:
    print('ERROR: wtf, qué versión de python es esta?')