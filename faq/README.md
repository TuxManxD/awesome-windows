<h3 align="center"> <a href="https://github.com/TuxManxD/awesome-windows"> <img width=25px src="https://siteicon.vercel.app/icon/terminal.png"> Tweaks</a> | <a href="https://github.com/TuxManxD/awesome-windows/tree/main/apps"> <img width=25px src="https://siteicon.vercel.app/icon/settings.png"> Apps</a> | ❓ FAQ | <a href="https://github.com/TuxManxD/awesome-windows/tree/main/iso"> <img width=25px src="https://siteicon.vercel.app/icon/disk.ico"> ISO</a></h3>

### How do I pin UWP to my desktop?
```powershell
shell:AppsFolder
```
### View all UWP apps
```powershell
Get-AppxPackage –AllUsers | Select Name, PackageFullName
```
### Full command, for detailed analysis
```powershell
Get-AppxPackage –AllUsers
```

### How does Explorer sort special characters in files?
<img width=40% src="https://github.com/awesome-windows11/windows11/assets/87380272/a218937d-b08e-42e3-a9d5-f5057237439a">


### Как посмотреть последние файлы открытые на ПК?
```
%UserProfile%\AppData\Roaming\Microsoft\Windows\Recent
```
### Как включить режим бога панель управления (GodMode?)
Не работает в последних версиях, где панель управления вырезали (2004+)

Создайте папку с именем:
```
Settings.{ED7BA470-8E54-465E-825C-99712043E01C}
```
