# Emp_payroll
This is basically an Employee payroll (Server-Client) generation application using RMI technique
Installations required:
1)IntelliJ IDEA (or Any java compatible editor)
2)Amazon Coretto version 16 SDK (or JDK version 16 or below since RMI is deprecated in recent versions)
3)mysql jar file (for backend database connection)
4)MysQL WorkBench

Commands to run an RMI program in terminal:
1) compile all the classes
2) rmic Emp (This is to generate Stub & Skeleton classes)
3) start rmiregistry (This will open a window which has to be minimized and kept)
4) Run Reg class i.e java Reg
5) Open another terminal where UI(Client) has to be run i.e java UI
