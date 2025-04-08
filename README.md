# bigdata3
big data assi3
Assignment No. 3
Use Hadoop's built-in commands to manage files and directories.
1. Create Directories in HDFS.
hdfs dfs –mkdir firstdir
2. Upload Files from Local File System to HDFS
Use the -put command to upload files from your local file system to HDFS.
hdfs dfs –put firstfile.txt /user/cloudera/firstdir 
3. List Files in a Directory
Use the -ls command to list the files in an HDFS directory.
hdfs dfs –ls  /user/cloudera/firstdir/
5. Display the Contents of a File
Use the -cat command to display the contents of a file in HDFS.
hdfs dfs -cat  /user/cloudera/firstfile.txt
6. Copy Files from HDFS to Local File System
Use the -get command to copy files from HDFS to your local file system.
hdfs dfs -get  /user/cloudera/firstdir/firstfile.txt /home/cloudera/lindir  
7. Delete a File in HDFS
Use the -rm command to remove a file from HDFS.
hdfs dfs -rm  /user/cloudera/firstdir/firstfile1.txt 
7. Delete a Directory in HDFS
Use the -rm -r command to delete a directory and its contents from HDFS.
hdfs dfs -rm -r /user/cloudera/firstdir  (For Non Empty Directory
hdfs dfs -rmdir  /user/cloudera/firstdir     (For Empty Directory )
