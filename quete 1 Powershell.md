# Equivalence des commandes bash / Powershell

_cp -->      Copy-Item_
_rm -->      Remove-Item_
_cd -->      Set-Location_
_mkdir -->   mkdir_
_man -->     help_
_history --> Get-History_
_alias-->    Get-Alias_
_cat -->     Get-Content_






# cp

PS C:\Users\b> Get-Command -Name cp

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Alias           cp -> Copy-Item**                                                                                                                                          

# rm


PS C:\Users\b> Get-Command -Name rm

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Alias           rm -> Remove-Item**                                                                                                                                        


# cd

PS C:\Users\b> Get-Command -Name cd

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Alias           cd -> Set-Location**                                                                                                                                       

# mkdir

PS C:\Users\b> Get-Command -Name mkdir

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Function        mkdir**                                                                                                                                                    

# man

PS C:\Users\b> Get-Command -Name man

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Alias           man -> help**                                                                                                                                              

# history

PS C:\Users\b> Get-Command -Name history

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Alias           history -> Get-History**  

# alias

 Get-Help Get-Command -online
 
**recherche --> alias --> Get-Alias**

# cat

PS C:\Users\b> Get-Command -Name cat

CommandType     Name                                               Version    Source                                                                                     
-----------     ----                                               -------    ------                                                                                     
**Alias           cat -> Get-Content**                                                                                                                                       
                                                                                                                               