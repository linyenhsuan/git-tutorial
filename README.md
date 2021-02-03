## git 指令

1. `git init`：初始化資料夾使資料夾可以用git追蹤該改
2. `git status`：顯示目前狀態
3. `git add .`：將所有更改加入暫存區
4. `git commit -m "..."`：確認更改
5. `git log`：查看所有紀錄
6. `git remote -v`：顯示遠端連結
7. `git push 暱稱`：將專案推送到遠端連結


<table>
<tr>
<th>編輯區</th>
<th>暫存區</th>
<th>紀錄區</th>
</tr>
<tr>
<td>123.py</td>
<td>
main.py</td>
<td></td>
</tr>
</table>

----

**`
git add .` 完後變成這樣**

<table>
<tr>
<th>編輯區</th>
<th>暫存區</th>
<th>紀錄區</th>
</tr>
<tr>
<td></td>
<td>
123.py<br>
main.py</td>
<td></td>
</tr>
</table>

----

**`git commit` 確定紀錄**

<table>
<tr>
<th>編輯區</th>
<th>暫存區</th>
<th>紀錄區</th>
</tr>
<tr>
<td></td>
<td></td>
<td>123.py<br>main.py</td>
</tr>
</table>

----

**做了一些更改變成這樣**

<table>
<tr>
<th>編輯區</th>
<th>暫存區</th>
<th>紀錄區</th>
</tr>
<tr>
<td>main.py</td>
<td></td>
<td>123.py</td>
</tr>
</table>