```
mkdir <任意の名前>
cd <任意の名前>
~/.bash_profileへexport GO111MODULE=onを追加(GOPATHモードからGO modulesモードへ移行)
go get -u github.com/spf13/cobra/cobra(※gitのバージョンが低いとエラーが発生する)
cobra init lt2
```