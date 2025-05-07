# gitignore_cheatsheet

Gitignore cheatsheet
<table>
<tr>
<td>Pattern</td>
<td>Explanation</td>
<td>Examples</td>
</tr>
<tr>
<td>name_file</td>
<td>All files with the name_file will be ignored</td>
<td>/name_file, /lib/name_file</td>
</tr>
<tr>
<td>_.cache All</td>
<td>files ending with .cache</td>
<td>app.cache, temp.cache</td>
</tr>
<tr>
<td>/local.env</td>
<td>Only root-level local.env file</td>
<td>/local.env (not config/local.env)</td>
</tr>
<tr>
<td>!/main.c</td>
<td>Exception: Keep main.c despite other rules Overrides</td>
<td>_.c exclusion</td>
</tr>
</table>
