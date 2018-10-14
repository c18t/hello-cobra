# hello-cobra
GOで全ウェブサイトCLI化計画を読んだときのお試しプロジェクトです

## Project Making
```sh
$ go get github.com/spf13/cobra/cobra
$ cobra init github.com/c18t/hello-cobra
$ cd $GOPATH/src/github.com/c18t/hello-cobra
$ cobra add goodbye
$ go install
```