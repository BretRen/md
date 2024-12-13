# Welcome to StackEdit!

Hi! I'm your first Markdown file in **StackEdit**. If you want to learn about StackEdit, you can read me. If you want to play with Markdown, you can edit me. Once you have finished with me, you can create new files by opening the **file explorer** on the left corner of the navigation bar.

a
# Files

StackEdit stores your files in your browser, which means all your files are automatically saved locally and are accessible **offline!**

## Create files and folders

The file explorer is accessible using the button in left corner of the navigation bar. You can create a new file by clicking the **New file** button in the file explorer. You can also create folders by clicking the **New folder** button.

## Switch to another file

All your files and folders are presented as a tree in the file explorer. You can switch from one to another by clicking a file in the tree.

## Rename a file

You can rename the current file by clicking the file name in the navigation bar or by clicking the **Rename** button in the file explorer.

## Delete a file

You can delete the current file by clicking the **Remove** button in the file explorer. The file will be moved into the **Trash** folder and automatically deleted after 7 days of inactivity.

## Export a file

You can export the current file by clicking **Export to disk** in the menu. You can choose to export the file as plain Markdown, as HTML using a Handlebars template or as a PDF.


# Synchronization

Synchronization is one of the biggest features of StackEdit. It enables you to synchronize any file in your workspace with other files stored in your **Google Drive**, your **Dropbox** and your **GitHub** accounts. This allows you to keep writing on other devices, collaborate with people you share the file with, integrate easily into your workflow... The synchronization mechanism takes place every minute in the background, downloading, merging, and uploading file modifications.

There are two types of synchronization and they can complement each other:

- The workspace synchronization will sync all your files, folders and settings automatically. This will allow you to fetch your workspace on any other device.
	> To start syncing your workspace, just sign in with Google in the menu.

- The file synchronization will keep one file of the workspace synced with one or multiple files in **Google Drive**, **Dropbox** or **GitHub**.
	> Before starting to sync files, you must link an account in the **Synchronize** sub-menu.

## Open a file

You can open a file from **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Open from**. Once opened in the workspace, any modification in the file will be automatically synced.

## Save a file

You can save any file of the workspace to **Google Drive**, **Dropbox** or **GitHub** by opening the **Synchronize** sub-menu and clicking **Save on**. Even if a file in the workspace is already synced, you can save it to another location. StackEdit can sync one file with multiple locations and accounts.

## Synchronize a file

Once your file is linked to a synchronized location, StackEdit will periodically synchronize it by downloading/uploading any modification. A merge will be performed if necessary and conflicts will be resolved.

If you just have modified your file and you want to force syncing, click the **Synchronize now** button in the navigation bar.

> **Note:** The **Synchronize now** button is disabled if you have no file to synchronize.

## Manage file synchronization

Since one file can be synced with multiple locations, you can list and manage synchronized locations by clicking **File synchronization** in the **Synchronize** sub-menu. This allows you to list and remove synchronized locations that are linked to your file.


# Publication

在 StackEdit 中发布文件让您可以轻松地在线发布文件。一旦您对文件感到满意，您就可以将其发布到不同的托管平台，例如** Blogger **、** Dropbox **、** Gist **、** GitHub **、** Google Drive **、** WordPress **和** Zendesk **。使用[ Handlebars 模板](http://handlebarsjs.com/) ，您可以完全控制导出的内容。

>在开始发布之前，您必须在**发布**子菜单中链接一个帐户。

##发布文件

您可以通过打开**发布**子菜单并单击**发布到**来发布文件。对于某些位置，您可以选择以下格式：

- Markdown：将 Markdown 文本发布到可以解释它的网站上（例如** GitHub ** ）， - HTML：通过 Handlebars 模板发布转换为 HTML 的文件（例如在博客上）。


##更新出版物

发布后，StackEdit 会将您的文件链接到该出版物，方便您重新发布。修改文件后，如果想更新出版物，请点击导航栏中的**立即发布**按钮。

> **注意：**如果您的文件尚未发布，则**立即发布**按钮将被禁用。 

##管理文件发布

由于一个文件可以发布到多个位置，因此您可以通过点击**发布**子菜单中的**文件发布**来列出和管理发布位置。这允许您列出和删除链接到您的文件的发布位置。


# Markdown 扩展

StackEdit 通过添加额外的** Markdown 扩展**来扩展标准 Markdown 语法，为您提供一些不错的功能。

> **专业提示：**您可以在**文件属性**对话框中禁用任何** Markdown 扩展**。 


##智能裤子

SmartyPants 将 ASCII 标点符号转换为“智能”印刷标点 HTML 实体。例如：

| | ASCII                           | HTML                          | |----------------|-------------------------------|-----------------------------| |单反引号| ` '这不是很有趣吗？' ` | '这不是很有趣吗？'             | |引号          | ` "这不是很有趣吗？" ` | "这不是很有趣吗？"             | |破折号          | ` -- 是 en-dash， --- 是 em-dash ` | -- 是 en-dash， --- 是 em-dash |                

            
            



##凯特克斯

您可以使用[ KaTeX ](https://khan.github.io/KaTeX/)渲染 LaTeX 数学表达式：

满足$ \Gamma ( n ) = ( n-1 ) ! \quad \forall n \in \mathbb N $的* Gamma 函数*是通过欧拉积分

$$                                                   \Gamma                                                   ( z ) = \int _0^ \infty t^ { z-1 } e^ { -t } dt \, . $$



>您可以在[这里](http://meta.math.stackexchange.com/questions/5020/mathjax-basic-tutorial-and-quick-reference)找到有关** LaTeX **数学表达式的更多信息。


UML图

你可以使用[ Mermaid ](https://mermaidjs.github.io/)渲染 UML 图。例如，这将生成一个序列图：

```美人鱼
序列图
爱丽丝 ->> 鲍勃：你好，鲍勃，你好吗？
鲍勃-->>约翰：你好吗，约翰？
鲍勃--x 爱丽丝：我很好，谢谢！
鲍勃-x 约翰：我很好，谢谢！
注意约翰的右边：鲍勃想了很久<br/>很久，太长了<br/>以至于文本<br/>一行都放不下。鲍勃-->爱丽丝：正在和约翰核对...爱丽丝->约翰：是的... 约翰，你好吗？```这将生成一个流程图：```mermaidgraph TD    A[默认节点]    B[圆角矩形] --> C[圆形]    D[椭圆形]    style B fill:#f96,stroke:#000,stroke-width:2px,rx:10,ry:10;    style C fill:#8fa,stroke:#333,stroke-width:2px,shape:circle;    style D fill:#9cf,stroke:#000,stroke-width:2px,shape:ellipse;```



















<!--stackedit_data:
eyJoaXN0b3J5IjpbNDkxMjIwNjQ0XX0=
-->