# EECS 201 HW 6
uniqname: skunkel

## Question 1
``` 1
^ indicates the begining of the string, and the string starts with whatever is after the symbol.
```

## Question 2
``` 2
$ indicates the end of the string, and the string ends right with that was before the symbol.
```

## Question 3
``` 3
. takes the place of a letter. 
```

## Question 4
``` 4
grep -c ^...$ cracklib-small
```

## Question 5
``` 5
grep -c ^[a-z][a-z][a-z]$ cracklib-small
```

## Question 6
``` 6
for vowel in a e i o u; do echo -e "$(grep -c ^$vowel cracklib-small) \t $vowel"; done | sort -rn
For each vowel, a, e, i, o, u prit out the number of words in cracklib-small that start with that vowel and then print the vowel (after a tab). When you print this print it in reverse numerical order (biggest to smallest)
```

## Question 7
``` 7
sort <(cat american-english british-english) | uniq -u | wc -l
```

## Question 8
``` 8
sort <(cat american-english cracklib-small) | uniq -d | wc -l
```

## Question 9
``` 9
The command  grep -v ' \*' returns all files that do not contai, space \ followed by any other character, in them (the -v  creates a list of all of the excluded files)

```

## Question 10
``` 10
Git grep does not search untracked files, and I tested this by making a new file that contains the phrase "insert_list" in my local repo and then running git grep. When I did this, the file that I had just made but not staged or committed did not show up in the list produced.
```

## Question 11
``` 11
Git grep does search staged files that have not yet been committed. To test this, I made a file named test_file that contained the phrase "insert_list", and then I used git add insert_list to stage the file. When I ran git grep again, the text from test_file showed up in the list produced, so I know that git grep must search tracked but uncommitted files.
```