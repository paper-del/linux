   grep allows find things in text
    grep fox sample.txt looking only for "fox" in file
    grep -e "-v" see -v like a text not a command
    grep -i dont see diference betwen cappital and normal letters
    grep -c shows how much lines have a pattern
    grep -o shows exact moment when text arrive
    greo -f plik1 plik2 first file is a pattern to next file
 piping grep
    env | grep -i User
    ls /somedir | grep '.txt$' looking for only txt files