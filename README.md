### Use [moco](https://github.com/dreamhead/moco) As mock server

---

This is a demo about how to make a web mock server by `moco`.

Describtion of all files and folder as follows:
  
* `jar` package is used to execute the `moco` command.
* Put all mock-api in the folder that `resources`.
* Compiled `generate.js` with NodeJs, progressing files under resources included in `api.json`.
* Use `mockServer.sh` run mock server. 

---

这是一个Demo, 关于如何使用 `moco` 搭建一个 web 的 mock server。

其中文件夹以及各个文件的描述如下：

* `jar` 包用来执行 `moco` 的命令。 
* `resources` 文件夹下放着所有的 mock-api 文件。
* `generate.js` 是用 `nodejs` 编译，可以读 resources 下的文件并在处理后 include 到 `api.json` 文件。
*  `mockServer.sh` 文件， 用来启动 mock server 的脚本。