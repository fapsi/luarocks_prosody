# luarocks_prosody
Building prosody in default/stable branch with luarocks. All Credits go to https://github.com/daurnimator who created the initial template. 

Please note: Set environment variables(`PROSODY_SRCDIR`,`PROSODY_CFGDIR`,`PROSODY_DATADIR`,`PROSODY_PLUGINDIR`) accordingly and adapt the prosody.cfg.lua with your preferences.

Note on some systems (e.g. centos 7) you will need the following compile flag in your `.luarocks/config-x.x.lua`:
 
```
variables = {
  CC= "gcc -std=c99"
}
```
