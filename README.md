# MySQL
## Description
GFL's MySQL plugin that handles the database connection to the MySQL server.

## Requirements
This plugin requires GFL's Core [plugin](https://github.com/GFLClan/SM-Core) to be added to the game server and enabled.

## ConVars
* `sm_gflsql_name` => The key name to the array providing the MySQL database details in `configs/databases.cfg` (default `"gflmysql"`).
* `sm_gflsql_retryvalue` => How often to retry the database connection if down in seconds (default `30`).
* `sm_gflsql_debug` => Whether to enable verbose logging within the plugin (default `0`).

## Credits
* [Christian Deacon](https://www.linkedin.com/in/christian-deacon-902042186/) - Creator