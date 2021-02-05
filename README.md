# NTLM package

Download the ntlm folder and copy to the path:


``` bash
Python27\Lib
```

just use sqlmap, I leave you an example:

``` bash

C:\Tools\sqlmapproject> python sqlmap.py -u "http://example.com/path/page.asp?id=1" --dbms "Microsoft SQL Server" -auth-type=NTLM -auth-cred="domain\user:pass" --all --dbs --risk 3 --level 5
```

### Credits:

Of course to the creators of the ntlm package :ok_hand: and also thank [@Asavior2](http://orange.tw/) :v:
