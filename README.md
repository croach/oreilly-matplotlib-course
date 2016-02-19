# Mastering Matplotlib

Jupyter notebooks for my matplotlib course from O'Reilly Media.

# Setting Up Your Environment

All of the code for this course relies heavily on elements from the
python scientific stack. Unlike most python packages, those used by
the scientific community need to be compiled, for performance reasons,
and as such, they can be a bit tricky to install. The company
Continuum has effectively solved this problem for us though, by
creating a new distribution of Python that comes with many of these
tools already installed, and pre-complied versions of the rest are
just a single terminal command away. For this reason, we’ll be using
Anaconda as our python distribution for this course.

So, assuming you have Anaconda installed, you can simply run the
`conda env create` command from the directory containing this file to
create a new environment, called `mpl`, and install all of the
packages you need.

% conda env create -f environment.yml

Once the `create` command finishes, you can activate the new
environment by calling `source activate mpl`.

% source activate mpl

If everything worked correctly, you should now be able to run the code
for this course with the following command:

% jupyter notebook
