---
nocomment: " "
---

## 编辑前须知
首先，感谢您愿意为此手册做出改进。

在开始之前，请您阅读 [如何贡献](/how-to-contribute) 和 [格式规范](/format-specification) 页面，以便更有效地进行编辑

在阅读完之后，请点击下方的按钮进行编辑。

<a id="btn-startedit" style="padding: 0.75em 1.25em; display: inline-block; line-height: 1; text-decoration: none; white-space: nowrap; cursor: pointer; border: 1px solid #6190e8; border-radius: 5px; background-color: #6190e8; color: #fff; outline: none; font-size: 0.75em;">开始编辑</a>

<script>
	function getQueryVariable(name, dft)
	{
		var reg = new RegExp('(^|&)' + name + '=([^&]*)(&|$)', 'i');
		var r = window.location.search.substr(1).match(reg);
		if (r != null)
		{
			return unescape(r[2]);
		}
		return dft;
	}
	document.getElementById("btn-startedit").href = "https://github.com/su-gzno3ms/tech-guide/edit/main/docs" + getQueryVariable("ref", "");
</script>