Falls das Plugin verschoben wird / die Ordnerstruktur verändert oder umbenannt wird müssen die Verknüpfungen neu hergestellt werden.

Dazu sind folgende Schritte notwendig:

1. Open Excel -> Extras: Excel Addins / Plugins and delete `Excel2LaTeX`
2. Open Finder: CMD-SHIFT-H (Change to home directory) and then CMD-J (open view setting) > enable "Show Library folder" there.
3. Remove `com.microsoft.Excel` in `Library/Containers` folder.
4. Make Library folder invisible again
4. Restart Excel
5. Add Plugin again (Extras > Excel Addins)



More info here: https://github.com/krlmlr/Excel2LaTeX/issues/15
