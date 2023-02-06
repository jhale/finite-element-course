Software tools
==============

To ensure a consistent coding environment we will be using GitHub Codespaces.
GitHub Codespaces provide a cloud-based development environment for working on
code. Free GitHub accounts come with 120 hours of Codespace time per month
which should be plenty. You are welcome to use your own Python and git install,
but you will be responsible for troubleshooting.

First visit `jhale/finite-element-course
<https://github.com/jhale/finite-element-course>` and click *Use this template*
and then *Create a new repository*. Make your repository name
``finite-element-course-2023`` and make sure to click the Private box.

Next visit `GitHub codespaces <https://github.com/codespaces>` and click on
*New codespace*. Select the repository you created above and leave everything
else on the default settings.

The instructor will walk you through using the Codespace in class.

Python 
......

Your implementation will be written in Python based on a code skeleton
provided. This means that you'll need a certain familiarity with the
Python language. But don't panic! Python is a very easy language to
work with. This module will use Python 3. 

If you haven't done any Python before, then go through `the official
Python tutorial <https://docs.python.org/3/tutorial/index.html>`__. If
you have done a little Python but perhaps are not so familiar with the
object-oriented features such as classes, then you might like to refer to the
online book `Object-oriented Programming in Python for Mathematicians
<https://object-oriented-python.github.io>`__. We will be using classes
extensively in this course.

The Matlab-like array features of Python are provided by `Numpy
<https://www.numpy.org/>`__ for which there is a `helpful tutorial
<https://numpy.org/devdocs/user/quickstart.html>`__. There is also a
handy `guide for Matlab users
<https://numpy.org/devdocs/user/numpy-for-matlab-users.html>`__. In that context, the
code provided in this course will always use Numpy arrays, and never
Numpy matrices.

Git
...

Version control is a mechanism for recording and managing different
versions of changing software. This enables changes to be tracked and
helps in the process of debugging code, and in managing conflicts when
more than one person is working on the same project. Revision control
can be combined with online hosting to provide secure backups and to
enable you to work on code from different locations.

In this module, you'll use verion control to access the skeleton
files, and to update those files if and when they change. You'll also
use the same revision control system to record the edits you make over
time and to submit your work for feedback and, eventually, marking.

We will be using the revision control system `git <http://git-scm.com/>`_,
which is the current state of the art and is widely adopted. We'll be combining
git with the online hosting service `GitHub <http://github.org>`_.

The command line
................

A lot of the routine activity involved in this module revolves around
executing commands on the command line. For example you use the
command line to work with the revision control system. 

.. proof:exercise:: 

    If you're not familiar with the Linux command line, then follow at least
    the first two sections of the `Software Carpentry Unix Shell lesson
    <https://swcarpentry.github.io/shell-novice/>`__. That guide focusses on
    the Bash shell, but zsh and the Windows Powershell use very similar
    commands.
