## Container Setup Steps
1. Install Microsoft ODBC driver following these [instructions for Debian Linux](https://learn.microsoft.com/en-us/sql/connect/odbc/linux-mac/installing-the-microsoft-odbc-driver-for-sql-server?view=sql-server-ver16&tabs=debian18-install%2Calpine17-install%2Cdebian8-install%2Credhat7-13-install%2Crhel7-offline)

2. Initial.ize conda and install packages
```
conda init bash
conda install Faker --no-warn-script-location
conda install pyodbc
```