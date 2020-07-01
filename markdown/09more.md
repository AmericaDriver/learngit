#### 支持的HTML元素

不在markdown涵盖范围之内的标签，都可以直接在文档里面用html编写

目前支持的html元素有:<kbd><b><i><em><sup><sub><br>等

使用<kbd>Ctrl</kbd>+<kbd>Alt</kbd>+<kbd>Del</kbd>重启电脑

---

####  转义

使用反斜杠显示特定字符

```
**文本加粗**
**转义星号，正常显示**
```

效果如下:

**文本加粗**

\*\*转义星号\*\*

---

#### 公式

当你需要在编辑器中插入数学公式时，可以使用两个`$$`包裹`Tex`或`Latex`格式的数学公式来实现。提交后，问答和文章页会根据需加载`Mathjax`对数学公式进行渲染。

	$$
	\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
	\mathbf{i} & \mathbf{j} & \mathbf{k} \\
	\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
	\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
	\end{vmatrix}
	${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
	$$
$$
\mathbf{V}_1 \times \mathbf{V}_2 =  \begin{vmatrix} 
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial X}{\partial u} &  \frac{\partial Y}{\partial u} & 0 \\
\frac{\partial X}{\partial v} &  \frac{\partial Y}{\partial v} & 0 \\
\end{vmatrix}
${$tep1}{\style{visibility:hidden}{(x+1)(x+1)}}
$$



