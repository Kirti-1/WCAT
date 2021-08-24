__WCAT : Cat(Concatenate)__
__................................................__
_This project includes wcat commands, based on cat commands of linux, I have made clone of cat commands in which manipulation with files and its content is done._

```javascript
node index.js -r a.txt
```
> \*wcat\* is added to package.json file and to your environment variables using 
```#!/usr/bin/env node```
>so from now we can use \*wcat\* instead of \*node index.js\*

>ALL WCAT COMMANDS INCLUDED

1. __wcat filename1 filename2 filename3__ 
> read all the files and display the content of all the files mentioned.
2. __wcat -rs filename1 filename2__ 
> remove all the spaces in the file and then print it, from all the files mentioned.
3. __wcat -rn filename1 filename2__
> remove new line from file, from all the files mentioned.
4. __wcat -rmsc filename1 filename2__ 
> remove all special characters except A-Za-z, from all the files mentioned.
5. __wcat -rsc filename1 .'&'__
> remove secondary character given after dot(.) identifier, all the '&' character will be removed from the files mentioned.
6. __wcat -s filename1__
> add sequence of 1,2,3,...,n where n is the number of lines, from all the files mentioned.
7. __wcat -sn filename1__
> add sequence of 1,2,3,...,n where n is the number of lines only for non empty lines, from all the files mentioned.
8. __wcat -rel filename1__ 
> remove all the extra lines, from all the files mentioned.
9. __wcat (dest file) -w (src file)__
> _fileDest -w fileSrc_ - write the content of fileSrc into fileDest
10. __wcat (dest file) -a (src file)__
> _fileDest -a fileSrc_ - append the content of fileSrc into fileDest
11. __wcat -relmod filename1__ 
> keeps only one empty line, removes all the other extra lines present from all the files mentioned.


