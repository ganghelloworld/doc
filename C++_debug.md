compile err
-----------
<table>
<tr>
<th>Error info</th><th>How to do</th>
</tr>
<tr>
<td>"ostream_...."</td><td>check the class{};</td>
</tr>
<tr>
<td>"segment err"</td><td>check new and delete</td>
</tr>
<tr>
<td>"invalid int[int]"</td><td>check assign int to int[]</td>
</tr>
<tr>
<td>"func() no decalare in this scope"</td><td>check o.func() -> func()</td>
<tr>
<td>
"error: invalid use of member (did you forget the ‘&’ ?)" code:

	while(prlm->getState() != RSSListModel::finished);
</td><td>global var is not in this namespace</td>
</tr>
</table>




logical err
-----------
<table>
<tr>
<th>Error info</th><th>How to do</th>
</tr>
<tr>
<td>loop out wrong</td><td>check loop varibles (i; ; j++)</td>
</tr>
<tr>
<td>compute is alway zero</td><td>check assign float to int</td>
</tr>
</table>

