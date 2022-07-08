# "Hello World (Colab)" Exercise

![a screenshot of a colab notebook](/img/exercises/hello-world/colab-notebook.png)

## Learning Objectives

In this exercise, we'll practice using the Google Colab platform for the first time, gain familiarity with Python notebooks, and practice a rudimentary version control process of saving our notebooks to GitHub.

## Prerequisites

This exercise assumes you have already signed up for a GitHub account.

You're also encouraged to review and reference this [Markdown Guide](https://www.markdownguide.org/).

For more info about Colab, see:
  + https://colab.research.google.com/notebooks/intro.ipynb
  + https://colab.research.google.com/notebooks/basic_features_overview.ipynb


## Instructions

  1. On GitHub.com, create a new repository named something like "my-notebooks", and importantly include a "README.md" file. We'll refer to this as the "remote repository".
  2. Use [Google Colab](https://colab.research.google.com/) to create a new notebook document, and give it a title like "My First Notebook".
  3. In the notebook, create a new text cell and write some markdown in it (like the example markdown below).
  4. In the notebook, create a code cell and write some Python code in it (like the example code below).
  5. "Run" the notebook to see the output of your code cell.
  6. In the notebook, click "File" > "Save a copy in GitHub" to try to save the notebook to the "my-notebooks" repo you just created. You will be asked to authenticate with your GitHub account.
  7.  View your remote repository on GitHub and verify the notebook document has been saved there. Also verify your ability to view the notebook document on GitHub.

Example markdown:

```
# My First Notebook!

This is a text cell. It uses the markdown language. The line above is a heading, starting with the "#" sign. Remember "#" means something different in Markdown than it does in Python.

We can make links like [this](https://github.com/prof-rossetti/intro-to-python).

And lists too:

  + Item 1
  + Item 2
  + Item 3

For more information about Markdown syntax, see the [Markdown Guide](https://www.markdownguide.org/basic-syntax/).
```


Example Python code:

```py
# This is some example Python code
# These lines starting with "#" are "comments"
# Remember "#" means something different in Markdown than it does in Python

print("HELLO WORLD!")

x = 2 + 2
print(x)
```

## Success Criteria

Once you see the changes reflected in your remote project repository on GitHub.com, you have succeeded. Edit your existing text and code cells, and/or create new ones, then repeat steps 5-7 at least once for good measure.

![a screenshot of a colab notebook saved to a github repo](/img/exercises/hello-world/notebook-on-github.png)
