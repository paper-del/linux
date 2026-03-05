join command merges files into one with close data
like file 1
1 apple 
2 orange
3 fruit
file 2 
fruit
fruit
vegetable 
join file1 file2 
1 apple fruit
2 orange fruit
3 fruit vegetable
or join -1 2 -2 1 
