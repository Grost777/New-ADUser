# New-ADUser
New-ADUser -Name "Test User2" -GivenName "Test" -Surname "User2" -SamAccountName "testuser2" -UserPrincipalName "testuser2@contoso.com" -Path "OU=Users,OU=Accounts,OU=SPB,DC=winitpro,DC=loc" -AccountPassword(Read-Host -AsSecureString "Input Password") -Enabled $true
