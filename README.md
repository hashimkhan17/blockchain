# blockchain


readme
1 - Download IPFS client ( Command Prompt ) https://dist.ipfs.io/#go-ipfs  

2 - Place IPFS folder and add its environmental variable

3 - Make sure IPFS can be called from anywhere using command Prompt

4 - create repository 
 > ipfs init

5 - Ipfs get and view ipfs readme file  
 > ipfs cat /ipfs/QmS4ustL54uo8FzR9455qaxZwuMiUhyvMcX9Ba8nUH4uVv/readme

6 - Check number of directories
 > ipfs ls /ipfs/QmS4ustL54uo8FzR9455qaxZwuMiUhyvMcX9Ba8nUH4uVv/

7 - view other file 
 > ipfs cat /ipfs/QmS4ustL54uo8FzR9455qaxZwuMiUhyvMcX9Ba8nUH4uVv/about    

8 - Upload new file
 > ipfs add "anyfile.ext"

9 - Download same file 
 > ipfs get "hash_CID"

10 - Download same file with proper extension
 > ipfs get "QmRHFV12qcftPzYT3LetKxQtW49GiMM6FPbBorABRC9eXf" > "FILENAME.EXT""

11 - Upload directory on the ipfs
 > ipfs add -r "directory name"

12 -  download directory
 > ipfs get "hash_CID"

13 - get JSON format of the directory and files
 > ipfs object get QmWsLj5xgDCz91XxzHb8AyK6uFhmfdsR6Qb3KCofjdRNid

 Now connect your self with a network
14 - Run ipfs daemon service
 > ipfs daemon

15 - Check how many peers are you connected with
 > ipfs swarm peers

16 - Now upload an html sample file using add command

17 - Take its cid and go to the Brave browser.

18 - On the brave browser write (In case it would show you that you have to install localnode then click install)
  ipfs://CID_HASH

19 - to open this on any other browser use
