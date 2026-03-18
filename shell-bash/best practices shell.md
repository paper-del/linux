1 use bash
2 make the first line be @!/usr/bin/env bash 
3 use .sh or .bash extension
4 use set -0 errexit at start of yout script
	so when the command fails bash exits instead of continuing rest
5 prefer to user set -o nounset 
6 use set -o pipefail
7 use set -o xtrace with a check ob $TRACE env variable
8 use [[]] for conditions in if while statements instead of [] or test
9 always quote variable access with double quotes
10 use local variables is functions
11 accept multiple ways that users can ask for help and reposnd is kind
12 when printing error messages redirect to stderr
13 use long options where possible (like --silent instead of -s)
14 if appropriate change to the scripts dierectory close to the start of the script
15 use shellcheck heed its warning

```
set -o errexit
set -o nounset
set -o pipefail
if [[ "${TRACE-0}" == "1" ]]; then
    set -o xtrace
fi

if [[ "${1-}" =~ ^-*h(elp)?$ ]]; then
    echo 'Usage: ./script.sh arg-one arg-two

This is an awesome bash script to make your life better.

'
    exit
fi

cd "$(dirname "$0")"

main() {
    echo do awesome stuff
}

main "$@"
```
