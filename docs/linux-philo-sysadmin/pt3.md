# 第三部分：功能

<!-- ch 7~16 -->

Function

在第三部分中，我们的启示不仅仅是在键盘上敲击命令，我们开始以更高级的方式应用基础知识。为了更好地利用命令行，我们开始扩展我们的命令行程序，并创建经过测试的、可移植的和可维护的 shell 程序，我们保存这些程序并可以重复使用，甚至共享。我们变成了“懒惰的管理员”，开始自动化一切。我们使用 Linux 文件系统层次结构以开放格式存储数据。

对于系统管理员来说, *Linux 理念的这一部分是关于让我们的工作更容易。我们使用命令行的功能，并应用一些新的原则来利用我们在第二部分中学到的东西，尽可能多地实现自动化，并创建适合我们的程序。*

系统管理员的自动化不是编译程序，因为创建、测试、发布和维护这些程序需要太多的时间和精力。面向系统管理员的编程是关于 shell 程序的，比如 BASH 编程，它是快速、开放和可移植的。

一些业内人士会认为 shell 编程不如用编译语言编写程序那么费力。这是不正确的，虽然我在某些地方使用了术语脚本和脚本，但是编写 shell 脚本和使用 c 一样是编程。shell 编程的优势是多方面的，我们将在本节中详细讨论这些优势。

让我们同意“脚本”和“程序”这两个词是可以互换的。所以当我说“程序”时，您可以理解为 shell 脚本，尤其是 BASH 脚本，因为 BASH 是几乎所有 Linux 发行版中的默认 shell。