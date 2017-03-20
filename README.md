echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/guizhenyu0512/test.git
git push -u origin master


<div data-role="page" id="pageone">
  <div data-role="header">
    <h1>嵌套的可折叠块</h1>
  </div>

  <div data-role="content">
    <div data-role="collapsible">
      <h1>点击我 - 我可以折叠！</h1>
      <p>我是可折叠的内容。</p>
      <div data-role="collapsible">
        <h1>点击我 - 我是嵌套的可折叠块！</h1>
        <p>我是嵌套的可折叠块中被展开的内容。</p>
      </div>
    </div>
  </div>

  <div data-role="footer">
    <h1>页脚文本</h1>
  </div>
</div> 

</body>
</html>
