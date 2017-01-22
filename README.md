# UEditor介绍：
UEditor富文本编辑器，可以用来提交内容时使用。

#UEditor使用方法
1.ueditor包可以直接拷贝到项目目录下。

2.ueditor目录下找到index.html,并把如下三行拷贝到你所需要添加编辑器的页面中:
<script type="text/javascript" charset="utf-8" src="ueditor.config.js"></script>
    <script type="text/javascript" charset="utf-8" src="ueditor.all.min.js"> </script>
    <!--建议手动加在语言，避免在ie下有时因为加载语言失败导致编辑器加载失败-->
    <!--这里加载的语言文件会覆盖你在配置项目里添加的语言类型，比如你在配置项目里配置的是英文，这里加载的中文，那最后就是中文-->
    <script type="text/javascript" charset="utf-8" src="lang/zh-cn/zh-cn.js"></script>

3.确定所需引入的输入框或者文本域id，例如<textarea id = "editor"  style="width:600px;height:200px"></textarea>然后添加
<script>
var ue = UE.getEditor('editor');
</script>
请开心的使用ueditor吧
