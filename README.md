# MySQL
## Description
GFL's MySQL plugin that handles the database connection to the MySQL server.

## Requirements
* [GFL Core](https://github.com/GFLClan/SM-Core) - The core of the GFL SourceMod plugins and includes useful natives for logging purposes.

## ConVars
* `sm_gflsql_name` => The key name to the array providing the MySQL database details in `configs/databases.cfg` (default `"gflmysql"`).
* `sm_gflsql_retryvalue` => How often to retry the database connection if down in seconds (default `30`).
* `sm_gflsql_debug` => Whether to enable verbose logging within the plugin (default `0`).

## Other
The `tables.sql` file can be imported into the MySQL database. This adds the necessary tables and data for sub-plugins using this module.

## Credits
* [Christian Deacon](https://www.linkedin.com/in/christian-deacon-902042186/) - Creator