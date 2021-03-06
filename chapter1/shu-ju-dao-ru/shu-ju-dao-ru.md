# 数据导入

数据导入支持从CSV文件，Excel文件，数据库导入数据到BI系统，本例以从CSV文件导入数据为例，演示数据数据导入功能。

1）点击系统左边 **数据导入** - **CSV导入** 菜单，系统进入数据导入页面，如下图：

![](/assets/import1.png)

2）点击**选择文件**菜单，上传CSV文件到系统。文件上传成功后，系统自动进入导入配置页面。

![](/assets/import3.png)

3\) 点击**数据预览**按钮预览上传的数据，如果您上传的文件包含标题，请勾选**第一行作为标题**复选框，如果系统中已经有表，直接点击**选择**按钮，如果是第一次导入，请点击**新建**按钮来新建一张目标表，新建表界面如下：

![](/assets/import4.png)

4）录入表名，中文名，备注等信息，请注意表名只能是英文字符，然后点击**表字段**选项卡设置表字段，如下图：

![](/assets/import5.png)

5）系统自动读取CSV文件的表头字段信息，并自动识别字段类型。当然如果识别的字段类型不对，您也可以手动设置。表字段类型分为文本，整数，小数， 日期等类型，请将字段类型设置为正确的类型，错误的类型会影响您的数据分析。是否分词只对文本类型起作用，默认不分词，当您的字段文本内容比较大的时候（比如大于100个字），建议您设置分词为Y。设置完成点击**确定**按钮完成表的创建。

6\) 表创建好以后，系统会自动映射目标表和Excel数据源字段的对应关系，如果映射有误或是未映射上，可点击字段进行修改，点击**开始导入**按钮导入数据到睿思云系统，导入过程中您可以终断导入。导入完成后点击**保存配置**按钮保存本次导入信息，保存的配置信息可以在 **数据导入** - **导入配置** 模块中找到。

