# Your-Regex
$sConsole = "Transferred:      243.269M / 3.341 GBytes, 7%, 72.603 MBytes/s, ETA 43s" $result = StringRegExp($sConsole, "\h*\d+%", 3) ConsoleWrite("Result: " &amp; $result[0] &amp; @CRLF)
