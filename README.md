# PS-Toggle-Comments
Toggle single and multiline comments in PowerShell ISE with keyboard shortcuts.

dot-source in $profile and add keybindings:
$psise.PowerShellTabs.SelectedPowerShellTab.AddOnsMenu.Submenus.Add("Insert Comment", {Insert-Comment}, "Ctrl+Shift+C") | Out-Null
$psise.PowerShellTabs.SelectedPowerShellTab.AddOnsMenu.Submenus.Add("Remove Comment", {Remove-Comment}, "Ctrl+Shift+X") | Out-Null
