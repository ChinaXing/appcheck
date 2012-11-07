appcheck:
         run command on remote host and get result to local host
         get max,min,avg statistic

example:

$ appcheck -g wwwebhost  -cpu idle -mem -load                

==========Appcheck-for======== -cpu-  -mem/f-  -load- 

1 ->           wwweb153166.cm6 97.76  | 3662.05m |  0.68  | 
2 ->           wwweb153163.cm6 97.61  | 3626.66m |  0.82  | 
3 ->           wwweb153105.cm6 97.64  | 3505.67m |  0.62  | 
4 ->           wwweb153048.cm6 97.43  | 3641.39m |  0.32  | 
5 ->           wwweb164115.cm3 98.21  | 3705.57m |  0.43  | 
6 ->           wwweb164114.cm3 98.31  | 3577.30m |  0.68  | 
7 ->           wwweb164107.cm3 98.03  | 3557.05m |  0.47  | 
8 ->           wwweb164106.cm3 98.21  | 3767.27m |  0.65  | 
------------------------------
  ->                       max 98.31  | 3767.27m |  0.82  | 
  ->                       min 97.43  | 3505.67m |  0.32  | 
  ->                       avg 97.90  | 3630.37m |  0.58  | 


==EXPLAIN
wwwebhost is a host cluster name
-cpu , -mem , -load are options to fetch from remote host

==HELP

use `./appcheck' to fetch a useage info page



2012-09-20 By Yunxing <yunxing.cyx@taobao.com>
