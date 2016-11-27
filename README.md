# hackingprogramming

Scripts that I find useful to make programming easier.

1) convert xls to csv with libre office

http://askubuntu.com/questions/379416/saving-xls-as-csv-with-libreoffice-calc


libreoffice --headless --convert-to csv --outdir somedir *.xls appears to work.

--headless stops Libreoffice from opening a window, so it just converts your files and then exits.

:writer_csv_Export after csv appears to be unnecessary.

It might also be a problem that /Data/ means a directory called Data at the filesystem root, not in your home directory. Just omit --outdir DIR and you'll get the output in the current directory.




2) making forms easy

https://formbuilder.online/


3)
