#  random-passwd

random-passwd is a simple python script to generate random passwords

## license

random-passwd is published under the term of
[GPLv3](https://www.gnu.org/licenses/gpl-3.0.txt).

## usage

to generate a random password and write it to the standard output:

```
random-passwd [--format=FORMAT-STRING]
```

the password generated has format FORMAT-STRING which is a combination
of letters:
  - a: any alphabetical character
  - n: any 0-9 digit
  - b: any alphabetical character or 0-9 digit
  - p: any punctuation character .,;:/#$-_=*%&
  - h: any hexadecimal characetr (0-9 or A-F)
  - .: any character in the above lists

the default format is bbbbbbbb