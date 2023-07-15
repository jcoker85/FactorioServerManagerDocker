# FactorioServerManagerDocker

This is an updated Dockerfile for the factorio-server-manager. 

Please see here for more details: https://github.com/OpenFactorioServerManager/factorio-server-manager/blob/develop/docker/README.md

Currently, the only change is adding the ability to add parameters to the server. Just add an environment variable with the key GAME_PARAMS and then add whatever parameters you need.

There is a list of available game parameters here: https://github.com/OpenFactorioServerManager/factorio-server-manager/wiki/Installation-and-Usage

For example: 

<code>--autostart --config /config/config.ini</code>

Note that --conf, --dir, and --port parameters are already included in the startup script and should not be added here. 
