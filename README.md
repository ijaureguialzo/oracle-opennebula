# oracle-opennebula

Servidor de base de datos con Oracle Linux 8 y Oracle Database 21c.

## Cambio de contraseña del usuario SYS

Acceder por SSH con el usuario `oracle`:

```shell
make ssh
```

Conectar con SQL*Plus:

```shell
sqlplus / as sysdba
```

Cambiar la contraseña:

```sql
alter
user sys identified by "12345Abcde";
```

## Referencias

- [Database Installation Guide for Linux](https://docs.oracle.com/en/database/oracle/oracle-database/21/ladbi/preface.html)
- [Oracle Database 21c installation on Oracle Linux 8 and connect with SQL Developer](https://dev.to/chittrmahto/oracle-database-21c-installation-on-oracle-linux-8-and-connect-with-sql-developer-26gc)
- [Oracle Database Software Downloads](https://www.oracle.com/database/technologies/oracle-database-software-downloads.html#db_ee)
- [Google Drive raw data?](https://stackoverflow.com/questions/24834877/google-drive-raw-data)
- [Automatic Startup and Shutdown](https://docs.oracle.com/en/database/oracle/oracle-database/21/ntqrf/automatic-startup-and-shutdown.html)
- [How to autostart the ORCLCDB sample DB on Oracle Linux 8.5](https://www.mybijourney.com/how-to-autostart-the-orclcdb-sample-db-on-oracle-linux-8-5/)
