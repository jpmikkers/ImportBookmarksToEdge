# ImportBookmarksToEdge
Powershell script to import bookmarks into Edge browser.
\
\
If you're looking for a way to import bookmarks into Google Chrome browser, visit the [ImportBookmarksToChrome](https://github.com/jpmikkers/ImportBookmarksToChrome) repository.

## Usage

```posh
Import-BookmarksToEdge -Urls @('https://www.youtube.com')
```

You can also specify import folder name (the default is 'PowershellImported'):

```posh
Import-BookmarksToEdge -Urls @('https://www.youtube.com') -FolderTitle 'MyImports'    
```
