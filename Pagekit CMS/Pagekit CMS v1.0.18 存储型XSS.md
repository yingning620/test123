1. 添加小工具： http://localhost:8080/index.php/admin/site/widget
![[Pasted image 20240822202546.png]]
2. 按照上图中的顺序执行，进入到编辑工具页面，然后写入恶意的payload
![[Pasted image 20240822202829.png]]
3. 保存之后，刷新页面，前端发现出现弹窗： http://localhost:8080/index.php
![[Pasted image 20240822202859.png]]
4. 回到后台，查看创建的工具详情，也会出现弹窗
![[Pasted image 20240822202957.png]]

-------------------------------------------------------------------------
1. Add a small tool :  http://localhost:8080/index.php/admin/site/widget
2. Execute them in the order shown in the image above, go to the edit tool page, and then write the malicious payload
3. After saving and refreshing the page, a pop-up window is found on the front end： http://localhost:8080/index.php
4. Go back to the backend and view the details of the created tool, which will also appear in a pop-up window