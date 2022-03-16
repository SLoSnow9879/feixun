# feixun
The FIR302B A2 router has remote command execution

Reproduction steps: 
1.Visit the login page of feixun fir302b A2router
Default password admin /admin 

![图片](https://user-images.githubusercontent.com/90661022/158557677-b71e4d84-0f9d-4123-b5fe-0cfa7dc64ad8.png)

2. Find the system tool → system diagnosis → Ping → IP address / domain name. There is remote command execution at Ping 
3. 

![图片](https://user-images.githubusercontent.com/90661022/158557652-7d93936a-a4dc-4f54-a271-87aa21a4ab6b.png)

3. Enter the website IP at the IP address / domain name, for example: 8.8.8.8 

4. Click Start diagnosis 

![图片](https://user-images.githubusercontent.com/90661022/158557706-da8e7d81-05b0-4d82-843d-02bc5fbc4a51.png)
 5. Use burp 
 
 ![图片](https://user-images.githubusercontent.com/90661022/158557760-2223f4e9-8d9b-4450-891e-62646675096f.png)
 

 Modify the IP address to 8.8.8.8|ls 
 That is, the command of IP plus execution 
 
![图片](https://user-images.githubusercontent.com/90661022/158557882-5704ae04-491e-4c00-9505-b1099eb48d08.png)


 Then click "contract awarding" and click "release" for all subsequent packages to execute the command successfully 
 
 Look at the diagnostic results. The command has been executed successfully 
 
![图片](https://user-images.githubusercontent.com/90661022/158557948-f3124ad4-dc59-43a4-8e69-942dd280da53.png)

