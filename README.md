# openiot-wiki

### git clone 到本地

<pre>
git clone git@github.com:OpenIoT-Hub/openiot-wiki.git
</pre>

### 修改 ./docs 文件夹中的相关的.md 文件，并完成html生成

<pre>
mkdocs serve
mkdocs build
</pre>

### 提交文件过程（亦可采用Github Desktop进行提交）
<pre>
git add .
git commit -m"comment" # comment = comment
git push [a new branch]
</pre>


### 部署过程
<pre>
mkdocs gh-deploy --force
</pre>
