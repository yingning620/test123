Hello, I found Stored XSS in pagekit version [1.0.18](https://github.com/pagekit/pagekit/releases)

**Here are the complete attack steps:**
1. Add a small tool :  http://localhost:8080/index.php/admin/site/widget
![image](https://github.com/yingning620/test123/blob/main/Pagekit%20CMS/attachments/Pasted%20image%2020240822202414.png)
2. Execute them in the order shown in the image above, go to the edit tool page, and then write the malicious payload
![image](https://github.com/yingning620/test123/blob/main/Pagekit%20CMS/attachments/Pasted%20image%2020240822202829.png)
3. After saving and refreshing the page, a pop-up window is found on the front end： http://localhost:8080/index.php
![image](https://github.com/yingning620/test123/blob/main/Pagekit%20CMS/attachments/Pasted%20image%2020240822202859.png)
4. Go back to the backend and view the details of the created tool, which will also appear in a pop-up window
![image](https://github.com/yingning620/test123/blob/main/Pagekit%20CMS/attachments/Pasted%20image%2020240822202957.png)

-------------------------------------------------------------------------
