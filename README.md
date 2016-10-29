# WDBASQL
==========
WDBASQL  means   Wilmix  NOSQL.(W*SQL) is  a  Securable  database  invented  by  wilmix  jemin  j  in  GDollar, C# ,and JAVA  .
No  need  to  write  SQL Queries but  to  pass  parameters  in  WDBASQL  database for PLSQL f(x)s. 
We can  also   write   WDBASql queries  like    SQL/Oracle  Queries.




UNIT:1: Introduction
==========================

Welcome  to    WDBASQL  security  programming  designed   by Jemin Information  Technology!
=====================================================================================================

What  is  meant   by  WDBASQL?
WDBASQL  means   Wilmix  NOSQL.(W*SQL)  invented  by  wilmix  jemin  j  in  GDollar,
C# ,and JAVA  .No  need  to  write  SQL Queries
but  to  pass  parameters  in  WDBASQL  database  PLSQL  functions.. WDBASQL  is  also
transport   data  from  SQLSERVER  to   WDBASQL  and  viceversa.
We can  also   write   WDBASql queries  like    SQLServer  Queries.
When  it  is   invented?
It  is  invented   by  wilmix jemin  j   in   year 2016.
Why  WDBASQL  is  most  important  for  software  development?
Since  it  provides  security  ,  transports  data  from   WDBASQL  to  SQLSERVER,oracle
and  viceversa.  And  it  will  connect   with  major   databases  like   Oracle,
SQlserver,etc. And  it  protect   the  hackers   and  unwanted   users 
stealing  the  data.

How  WDBASQL  database  Works?

WDBASQL    database  uses  WDBASQL  Editor.  WDBASQL(.dlls)    are responsible    for  
transporting  ,  executing   Query .  WDBASQL   did  not  contain  server; Instead  of that    it  
contain   only   WebConsole    to  see  the  HTML  outputs.

WDBASQL(W*SQL)  takes    the  data   from  Sqlserver  and   store  it.  We can  also   perform  
retrieval ,Encrypt,Decrypt   data , Select  particular  row, Join Operations, Aggegerate  tools,
etc. using  WDBASQL.

Which  you  can   learn  more  detail   in  Unit -II.
let  us   see  how  it  works? Why  it is     more  advanced?

Explanation:
===========

When  Users   type  WDBASQL(W*SQL)  Program   at  first  you  compile   the  db  program
using  compile   at  right  corner   of  the  editor.

And  Next  you   run the program    using   Run at   right   corner   of  the  editor.
When  you click  "RUN"  it   produces  .obj and  .exe  file  for  futhure  use    with   CDollar,
JAVA, Dotnet,   and  JDollar, JSAUCER,  etc.  So  You  can   selected  only   encrypted  (.obj)  file  
and  run   the  database   program.

SO  choose    the  .dll  file  to  run  WDBASQL   program .When  you    insert    a  data  in   a   
program   it  stores   it  in  WDBASQL encrypted  file  and  finally    it  retrieves   the  data    from  
encryted  file   for  futhure  use. WDBASQL   is  responsible    for  data security  with  data  
storage  and  retrieval management.You can   also    do  programmming   simillar  to  PLSQL
and  we can  change  the  theme   of  HTML  Output. You  can  see  the   output  in webconsole
by  pressing   RUNWDBASQL(*) button   at  the  right  corner  of  WDBASQL(*)  Editor.  



WDBASQL(*)
==========

Example-1:
=============
import  CDollar.WDBA.*;
import  java.util.*;
public class  manipulations

{


public  static   void  main(String  args[] )

{

try

{

String g = WDBASQL.WDBASQLS("datastores", "USEDATABASE", "dbpwds", "C:\\Programs\\WDBA\\WDBAProgramfiles\\WDBA-cod");  //path for  wdba   database

           


          String   t = WDBASQL.WDBASQLS("dbuser", "dbpwds", 1, "wilmix78", "wilmix78", 1, 5, g);
//user  credentials
           String s1 = "CREATETABLE from Telecom 0 to 0 , 1 to 7 ?= 6639 By 6639 f(x) : {SNO,CLASS,CHILDS}: {1,A,a1,2,A,a2,3,A,a3,4,B,b1,5,B,b2,6,B,b3,7,C,c1,8,C,c2,9,C,c3} :{2,4}";
//create   table    with  fields
            String s11 = "RIGHTJOIN from student 0 to 1 , 1 to 4 ?= emp For X f(x) : {0,1,2,3,4,5,6,7,8,9,10,11} : {0,1,2,3,4,5,6,7,8,9,10,11} : {0}";
// perform  right  join  between   two  tables   student  and  emp


String  s12 ="MATCH from Telecom 3 to 29 , 1 to 7 ?= C By 1 1 : {0} : {0} :{0}";
//Select  all  columns   that   match   with  'c'  char
String  s111 ="SELECTRVAL from Telecom 3 to 29 , 1 to 7 ?= C By 1 1 : {0} : {0} :{1}";
// select  all  rows   
String   s2 ="";

    

      
          System.out.println("jem="+WDBALIB.WDBAQUERY(  s1,  t));
            System.out.println("" + WDBALIB.WDBAQUERY(s11, t));

ArrayList ars= new  ArrayList();

ArrayList ar= WDBALIB.WDBAQUERY(s12, t);

ArrayList aryu= WDBALIB.WDBAQUERY(s111, t);

for  (int  i=1;i<=ar.size()-1;i+=2)

{

s2="Select from Telecom 3 to "+ar.get(i).toString() +" , 1 to 7 ?= X By 1 1 : {0} : {0} :{1}";

 ars.add( WDBALIB.WDBAQUERY(s2, t));




}



System.out.println(""+ars);

}


catch(Exception  e)  {}




}



}







UNIT:3: WDBASQL(WSQL*)  PLSQL Forms and Reports
==============================================

WDBA.writeln("html tags");
HTML.displayhtml("html file");

<TRY>  =>  try block

<CATCH>  =>  Catch block in  WDBASQL
<EXE>  => Exception

SYNTAX:
=======

<WNOSQL>
<PACK>

<DATALIB>  namespacename
<DATA>
public  <CLASS>  classname
{



public void main() 


{

<!WDBASQL  Statements  !>

}
}

</DATA>





State    the  Advantages  of  WDBASQL (*)   Database?
======================================================

a)  WDBASQL(*)   is   a  NOSQL  databases
b)  WDBASQL(*)   need  no  datasource  since  it  remotely connect  with
C# or  Dotnet  or  JSTAR  or  CWEB  or  java  or  JDollar  Program 
c) WDBASQL    also   has     SQL  Concepts  and  SQL  Advanced  concepts
d)  You    can  see  the    output    the   WEB  console
there  is  no  need   for   server
e)  WDBASQL    uses   cluster  memmory  management  to  protect  your
data   from  hackers ,etc.
f)  WDBASQL  will  Store   Huge  amount  of  data
ie  )  > Thrillion  Thrillion …….

g)  WDBASQL(*)    has   Userfriendly   WDBASQL cmd console
h) WDBASQL   Prevents   SQL  INJECTION
i) WDBASQL(*)  has  attractive  syntax.
j)  WDBASQL(*)   also   has   PLSQL to  execute  db
statements   as a batch.
k)  WDBASQL(*)  also  has   Advanced   oops   like  JAVA
and  C# 
l)  WDBASQL  is  a  Advanced   Database.
m)  WDBASQL  also  transfer  to   and  from   SQLSERVER  to WDBASQL Database.
n)  We  can  also   use  CDollar    dlls   with  WDBASQL
o)  WDBASQL   also  store  the  output  in  .EXE  format
p) WDBASQL  also  be  used   with  other  Programming languages  through
through  SQL  Server.   
q)WDBASQL  PLSQL  uses  API  format
which  hacker  or  unwanted  user   can'  use   it  in website.
r) We  can  use   WDBASQL  (.wdba)  data   for  futhure
use  with  cloud   database   WDBAJ$  at  GALAXYv.1  cloud  OS.
s)  It  is    easy  to use   and   Learnable
t) We  can  also   do  progrmming   in  WDBASQL  database
u) We  can  also  construct forms   and  reports 
v)  Here   CDollar-JAVA.util  packages  are used
since   it  mostly  interact with  C#  Program.
w)  No  Server    for  WDBASQL(*) db
x)  Occupies  only  less  amount  of  safe
y) Prevents   from  data  loss  by  CLUSTERRESTORE
z) Performs   Manipulations (WDBASQL(*) )  in
huge  amount  of  data  say   1 thrillion.
never makes   db  very  slow   since  datas  are  divided  into
batches.



WDBASQL(WSQL*)PLSQL  interaction with  native databases
===============================================================

For  SQL  Server
WDBA.writeln((manipulate.Signal("MANIPULATE","Select  *  from  student","student","sno,tmark,rank","?,?,?",4,"sun.jdbc.odbc.JdbcOdbcDriver","jdbc:odbc:dsn","sa","jemin","wilmix21")));

For  Oracle  Server
WDBA.writeln(""+manipulate.Signal("MANIPULATE","Select  *  from  student","student","sno,tmark,rank","?,?,?",4,"oracle.jdbc.driver.OracleDriver","jdbc:oracle:thin:@localhost:1521:xe","system","jemin","wilmix2")); 

note:  select  the  following  dll  which is   given below

 manipulate.dll  ,  ikvm.open.jdbc.dll to  compile  this  WDBASQL
plsql  program.


Note:
======
Kindly   see    the  WDBASQL  pdf   for  more   details  about  WDBASQL  Tutorial.



