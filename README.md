# scripts

## Scan Content On Files
 - grep -Ril "text-to-find-here" / (path: optional)
## Mime-type File
 - file --mime-type filename
## List Files and infos
 - find -maxdepth 1 -type f -ls -exec file -b {} \;
