# bash-tutorial

- set -e (exit when cmd return with non 0)

## Bash basics

## Command line editing

## Customize the environment

## Basic Shell programming


## Flow Control

```
if condition
then
    statements
[elif condition
    then statements...]
[else
    statements]
fi
```
conditon: a list of statements rather than usual boolean,Exit statuses are the only things an if construct can test.
-  bash provides two ways of testing a variety of conditions.[...],[[...]], word spliting and pathname expansion are not performed on the words within the brackets to the second.
- the spaces after the bracket [ and before the closing ] are required.
- the square brackets []surround expressions  that include  various types of  operators.
    - string comparisons:
        - str1=str2
        - str1!=str2
        - str1<str2
        -n str1  ( not null str)
        -z str1  ( null str, length is 0)

    - file attributes checkinng

```
for name [in list]
do
    statements that can use $name...
done


case expression in pattern1 )
statements ;; pattern2 )
             statements ;;
      ...
esac


select name [in list]
do
    statements that can use $name...
done

while conditiondo
statements...done

until command; do
    statements...done
```

## Command line options and Typed Variables

## I/O and Command Processing


## Process Handling

## Debug
