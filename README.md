# Python for the Lab

Welcome to the source files for the book Python for the Lab. This is the book used for the workshop [Python for the Lab](https://www.pythonforthelab.com/courses/). 

If you want to compile the book first clone it and then compile it with xelatex:

```bash
git clone git@github.com:PFTL/PFTL_Book.git
cd PFTL_Book
xelatex -shell-escape index.tex
```

You need to use `xelatex` in order to be able to use special unicode characters present in the text. 
The command `-shell-escape` is used in order to compile the code with the proper formatting (which 
is achieved through some Python scripts). 

If you would like to have a compiled version of the book, [contact us](https://www.pythonforthelab.com/about/)
