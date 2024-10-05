# streamlit_change_language
`streamlit_change_language`支持streamlit内置组件中的文本中英文切换的库.

功能特点：

- 支持streamlit内置组件中的文本中英文切换

使用方法：

- `from streamlit_change_language import cst`
- `cst.change(language='cn')`
-   language可选项为 `en-英文, cn-中文`

  
 

- 1、下拉框的choose英文，重启app后生效为中文
- 2、如果页面仍然全是英文，清除浏览器缓存
- 3、如果应用整体出现异常，重新安装streamlit即可
- 4、streamlit_change_language相关代码放在应用的主py文件下即可，不需要多次引用
- 5、根据language选项，支持中英互转
- 6、遗漏地方估计还有很多，碰到了可以评论告知
