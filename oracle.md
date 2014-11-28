Oracle Summary
--------------
### Pre Startup
* __SQL*Plus__
* __listener__
* __connect  --> sysdba__

### Startup
* __nomout --> instance__
* __mount --> control file  --> files__
* __open  --> datafile  --> recovery__

### SQL*Plus
* __user, role & privilege__
* __set__
* __SQL & PL/SQL__  
  DCL  -->  grant, revoke  
  DDL  -->  create, drop, alter, truncate ...  
  DML  -->  select, update, insert, delete ...  
  PL/SQL  procedure, function, trigger, package  
  SQL> select deptno, count(ename) from scott.emp group by deptno order by deptno  
  SQL> declare ... begin ... end;  
* __Transaction__  
ACID

### Objects
> SQL> select * from user_objects;  
table, view, sequence, index ...

### Backup & Recovery
*  __backup__
    * physical
    * logical
*  __recovery__
*  __SQL*Loader, exp/imp, expdp/impdp, RMAN__


### Tools
* __OEM__
* __PL/SQL__
* __Others__
