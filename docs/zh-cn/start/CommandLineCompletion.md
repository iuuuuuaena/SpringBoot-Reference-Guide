<h2>3.2.5 命令行补全</h2>

Spring Boot CLI包括为[BASH](https://en.wikipedia.org/wiki/Bash_%28Unix_shell%29)和[zsh](https://en.wikipedia.org/wiki/Z_shell) Shell 提供命令完成的脚本。您可以脚本（也称为spring）放在任何shell中，或将其放在个人或系统范围内的bash完成初始化中。在Debian系统上，系统范围的脚本位于```/shell-completion/bash```下，并且在启动新的Shell时将执行该目录中的所有脚本。例如，如果您是使用SDKMAN安装的，则要手动运行脚本，请使用以下命令：
```
$ . ~/.sdkman/candidates/springboot/current/shell-completion/bash/spring
$ spring <HIT TAB HERE>
  grab  help  jar  run  test  version 
```


<b>注：</b>如果使用Homebrew或MacPorts安装Spring Boot CLI，则命令行完成脚本会自动注册到您的Shell中。


