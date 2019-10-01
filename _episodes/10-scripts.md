---
title: "Python Scripts"
teaching: 5
exercises: 0
questions:
- "How can I run complete python programs all at once?"
objectives:
- "Write a python file."
- "Execute a python file, both in the script and out."
keypoints:
- "Python scripts are plain text files."
- "Run scripts using `python`"
- "Use `atom` for editing python files."
---

## Creating an executable python file

- Like shell scripts, you can save your code in a file

- Now create a directory somewhere called `swc-python`

- Open up `atom`, either by clicking on the icon or typing `atom` in
  your terminal.

- Now, in your terminal, create a new directory under `swc-python` called
  `scripts`.

- In atom, create a new file. In that file, type:
~~~
msg = "Hello world!")
print(msg)
~~~
{: .language-python}
  then save it as `test.py` in the `scripts`  directory.

- This is a python script file. Note that `.py` indicats a python file, but this
  is convention, not requirement.

- You can now run the script using
  ```
  $ python scripts/test.py
  ```

- Similarly, if you start up `ipython` again, from within `ipython` you can do
  ```
  In [1]: run scripts/test.py
  Hello world!

  In [2]: msg
  Out[2]: "Hello world!"
  ```
  which will run all the code in `test.py` as though entered into `ipython`.
