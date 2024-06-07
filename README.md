# Disable Windows Recall
Registry keys for disabling Recall feature in Windows 11. Keys are not yet created by default, and possibly be changed forcefully when Windows updates.

Disable Recall - User [HKEY_CURRENT_USER\Software\Policies\Microsoft\Windows\WindowsAI] "DisableAIDataAnalysis"=dword:00000001

Disable Recall - Machine (not yet official) [HKEY_LOCAL_MACHINE\SOFTWARE\Policies\Microsoft\Windows\WindowsAI] "DisableAIDataAnalysis"=dword:00000001
