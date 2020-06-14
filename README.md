# Tcp-server_test
实现了一个tcp_server的小例子。

在客户端输入telnet 127.0.0.1 3030
然后再在输入json字符串：{"jsonrpc":"2.0","method":"send_Transaction","params":[{"from":"0xe3fwi3fe","to":"0xeir34fe","gas":23}],"id":0}
运行 Tcp-server-test中的send_Transaction函数。

客户端得到运行结果：
{"jsonrpc":"2.0","result":"0xe3fwi3fe0xeir34fe","id":0}
