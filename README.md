# fiximports
a small hacky script to change imports & gofmt

fiximports -new-import 'github.com/r2d4/kube-client/$1' -old-import "k8s.io/(client-go|apiserver|apimachinery)" -regex .
