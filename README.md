# :part_alternation_mark: Monaco font for IDE
Patched Monaco font for use in popular IDEs and editors (e.g. PhpStorm/WebStorm/NetBeans/IntelliJ/etc.) 

## :question: Why?
**Monaco** is a nice font for the code. I really like it. But it looks ugly in the Java-based IDEs on Linux. I tried to google a solution for this but exiting options was really weird or has limitations. So, I decided make my own patch. 

## :point_up: Features
* Look line in Java-based IDEs (see screenshot section) and other 
* Cyrillic symbols support out-of-the-box
* Works on Linux and Windows

## :book: How to use
Just install it into your system and select in our favorite editor/IDE

#### Linux
1. Put ``Monaco.ttf`` into your ``~/.fonts``
2. Update font cache by running 

```bash
fc-cache -f -v
```
3. Select in your favorite editor/IDE

### Windows
1. Open ``Monaco.ttf`` and press `Install`
2. Select in your favorite editor/IDE


## :camera: Screenshots
[PHP] PhpStorm 8.0 (Linux)

![Monaco in PhpStorm](/screenshots/[php]-PhpStorm-8.0.png?raw=true "[PHP] PhpStorm 8.0 (Linux)")

[JS] GEdit 3.16 (Linux)

![Monaco in Gedit](/screenshots/[js]-GEdit.png?raw=true "[JS] GEdit 3.16 (Linux)")

[CSS] WebStorm 9 (Linux)

![Monaco in WebStorm](/screenshots/[css]-WebStorm-9.png?raw=true "[CSS] WebStorm 9 (Linux)")

[C#] MonoDevelop 5.9 (Linux)

![Monaco in MonoDevelop](/screenshots/[csharp]-MonoDevelop.png?raw=true "[C#] MonoDevelop 5.9 (Linux)")

## :heavy_check_mark: Support table
| Editor | Result | Notes |
| --- | --- | --- |
| IntelliJ IDEA & similar (PhpStorm/Webstorm/PyCharm/...) | :heavy_check_mark: | - |
| GEdit | :heavy_check_mark: | - |
| MonoDevelop | :heavy_check_mark: | - |

## :muscle: Contributing

Is it worked for you? You have found that it looks ugly in your favorite editor? Feel free to create PR at tell your story
