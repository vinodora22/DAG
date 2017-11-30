DAG.cpp contains code to print all possible path from vertex(having indegree '0') to last node(having '0' out degree).


Sample output:
Compile:
vinod@vinod-Latitude-3480:~$ g++ DAG.cpp -o DAG

Run:
vinod@vinod-Latitude-3480:~$ ./DAG 
0->1->3->NULL
0->1->5->NULL
0->2->5->NULL
4->NULL
6->2->5->NULL
vinod@vinod-Latitude-3480:~$ 

