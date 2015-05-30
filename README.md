# Monaco font for IDE
Patched Monaco font for use in popular IDE like PhpStorm/WebStorm/NetBeans/etc. 

### Why?
Monaco is a nice font for code. I really like it. But it looks ugly on my IDE. 
I was trying to find some solution in Google and I find some solution but it has ugly line height or works only on Windows or don't support cyrillic. 
Than I decide make own patch. 

### Features
* Nice looking in IDE based on Java (see screenshot section) and other 
* Cyrillic support
* Works on Linux/Windows

### How to use
Just install it into your system

##### Linux
1. Put ``Monaco.ttf`` into your ``~/.fonts``
2. Update font cache by running 

```bash
fc-cache -f -v
```


### Screenshots
[PHP] PhpStorm 8.0 (Linux)

![Monaco in PhpStorm](/screenshots/[php]-PhpStorm-8.0.png?raw=true "[PHP] PhpStorm 8.0 (Linux)")

[JS] GEdit 3.16 (Linux)

![Monaco in Gedit](/screenshots/[js]-GEdit.png?raw=true "[JS] GEdit 3.16 (Linux)")

[CSS] WebStorm 9 (Linux)

![Monaco in WebStorm](/screenshots/[css]-WebStorm-9.png?raw=true "[CSS] WebStorm 9 (Linux)")

[C#] MonoDevelop 5.9 (Linux)

![Monaco in MonoDevelop](/screenshots/[csharp]-MonoDevelop.png?raw=true "[C#] MonoDevelop 5.9 (Linux)")