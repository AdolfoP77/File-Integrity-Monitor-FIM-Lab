# File-Integrity-Monitor-FIM-Lab

In this lab we will create a File Integrity Monitor (FIM) using python, the code will check Hashes for Integrity and send an email when a file's integrity has been changed.

<br>

1.Import libraries (Hashlib).(The Python hashlib module is an interface for hashing messages easily
![Importlibrary](https://user-images.githubusercontent.com/107056915/174117624-90299b84-aa79-48f2-a532-6136f1ab088c.png)
2.Get the file location. (We are using a input field)
![get file location](https://user-images.githubusercontent.com/107056915/174117662-9e9d4d23-d73c-4e28-9c77-1db663dacdc4.png)
3.Create a Function to hash a file.
![create fynction to hash a file](https://user-images.githubusercontent.com/107056915/174117678-56529221-99cc-4074-ad38-4883cf6ac25a.png)
4.Declare Hash type. We are using md5
![declare hash type](https://user-images.githubusercontent.com/107056915/174117695-76b3db34-ed16-4c4d-9b79-03f8f6d2fd1b.png)
5.Open the file in read and binary mode.
![open the file im read and binary mode](https://user-images.githubusercontent.com/107056915/174117733-2f5984ca-3a7d-4679-9927-d705ad91b357.png)
6.Read and put the file into a variable.
![read the dile and put it iinto a variable](https://user-images.githubusercontent.com/107056915/174117751-cb2c9497-499f-4d93-a42a-bf2baa36bea2.png)
7.Hash the file.
![hash the file](https://user-images.githubusercontent.com/107056915/174117766-f07ae2b7-1a7b-4dfb-8415-3511f2dd1c5b.png)
8.Return in hexadecimal mode.
![return the file in hexadecimal form](https://user-images.githubusercontent.com/107056915/174117783-76870923-ebcf-418e-ac2c-54c8f6c5dce2.png)
9.Set baseline to be the Hash
![set the baseline to be the Hash](https://user-images.githubusercontent.com/107056915/174117789-77f4e49b-462d-464c-8a21-3eedbb54ce52.png)
10.Create while loop. (never stops)
![create loop that never stops ](https://user-images.githubusercontent.com/107056915/174117798-ba783845-b736-46d7-89fa-bf55464bfc42.png)
11.Check files hash
![check the files Hash](https://user-images.githubusercontent.com/107056915/174117809-cf621dc0-fd94-42e6-9f3b-69462a437cd8.png)
12.Compare to see if it changed.
![compare to see if it changed and warn us if it has](https://user-images.githubusercontent.com/107056915/174117820-292eb1d0-a221-41cd-b3e8-94450591db14.png)
13.Make sure baseline is updated.
![compare to see if it changed and warn us if it has](https://user-images.githubusercontent.com/107056915/174117820-292eb1d0-a221-41cd-b3e8-94450591db14.png)
14.Add Email notification to notify.
![server](https://user-images.githubusercontent.com/107056915/174117959-c66c6c04-379b-45f0-a00b-8c855a8eb7ba.png)
![email notifications](https://user-images.githubusercontent.com/107056915/174117935-b9db1278-0c0a-4a3d-84b4-12435fb8dff9.png)

 
 
  
