# Powershell-Sysinfo

A project with Powershell Scripting for fetch system information using RSAT in domain

Using this script, when you have RSAT installed on your system and having enough access to ADUC, you can have system information of your clients. To do that, I use computer objects in Active Directory Users and Computers (ADUC). Traditionally, for every computer object we had a description which is name of the user that work with that system. I wrote a search description and select systems and list information of systems.

My search script works with wildcard statements and if you write even part of a computer name or username, you can have every information you want.
