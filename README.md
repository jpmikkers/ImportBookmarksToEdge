# ImportBookmarksToEdge
Powershell script to import bookmarks into Edge browser

## Usage

```posh
Import-BookmarksToEdge -Urls @('https://www.youtube.com')
```

You can also specify import folder name (the default is 'PowershellImported'):

```posh
Import-BookmarksToEdge -Urls @('https://www.youtube.com') -FolderTitle 'MyImports'    
```
