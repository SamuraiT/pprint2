function pprint2(){
    enscript --pretty-print --line-numbers --color -o ./$1.ps $1
    ps2pdf $1.ps
}
