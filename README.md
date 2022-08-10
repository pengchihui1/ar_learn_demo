## 教程
10行hiro：https://medium.com/arjs/augmented-reality-in-10-lines-of-html-4e193ea9fdbf


## 官方项目测试
情况：手机端一直加载中，没反应
代码：资源都有加载

## 注意点
ios 上的 Chrome 不支持相机访问。铬问题。请在 iphone 和 ipad 上使用 safari

## 手机不能访问设置
错误：Says Webcam Error Name: Message: WebRTC issue! navigator.mediaDevices not present in your browser

这很容易纠正！不用担心。这不是你的代码错误，只是在你的浏览器中在 URL 的开头添加了 https:// 这个词，没错，我的朋友！在 http:// 末尾添加一个 s

例如：

http://realidad-augmentada.com.co/aplicacionAR.html – –不会工作

https://realidad-augmentada.com.co/aplicacionAR.html – –如果可行

我解释一下 http 和 https 的含义：

HTTP：缩写来自英文Hyper Text Transport Protocol，即超文本传输​​协议。基本上，它是一种请求-响应类型的协议，旨在定义和标准化作为网络一部分的不同设备之间执行的通信。要使系统存在，需要存在客户端和服务器。客户端发出请求，例如在浏览器中输入下载 URL，服务器给出响应——即下载开始。
 

HTTPS：是 HTTP 的安全版本，即安全超文本传输​​协议（英文，Hypertext Transfer Protocol Secure）。这样的系统是基于 HTTPS 和 SSL/TS 协议的组合。简而言之，这是访问 Internet 上可用信息的最安全方式。HTTPS 使用加密连接安全地传输数据。它使用一个公钥，允许接收者在接收到信息时对其进行解密。此密钥存在于服务器上，并包含在我们所知的 SSL 证书中。
截取的片段以及网络上对 http 和 https 的更详细解释：https: //www.segurisoft.es