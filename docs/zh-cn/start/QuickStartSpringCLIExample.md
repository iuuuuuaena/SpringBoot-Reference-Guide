<h2>3.2.7 Spring CLI示例快速入门</h2>

您可以使用以下Web应用程序来测试安装。首先，创建一个名为的文件app.groovy，如下所示：

```java
@RestController
class ThisWillActuallyRun {

    @RequestMapping("/")
    String home() {
        "Hello World!"
    }

}
```

然后从shell运行，如下所示：

```
$ spring run app.groovy
```

<b>注：</b>您的应用程序的首次运行速度很慢，因为太多依赖项需要下载。随后的运行要快得多。

在您喜欢的网络浏览器中打开```localhost:8080```。您应该看到以下输出：


```
Hello World!
```