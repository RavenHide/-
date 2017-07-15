# -用ssh登录一个机器（换过ip地址），提示输入yes后，屏幕不断出现y，只有按ctrl + c结束
 
错误是：The authenticity of host 192.168.0.xxx can't be established.
 
执行ssh  -o StrictHostKeyChecking=no  192.168.0.xxx　就OK
