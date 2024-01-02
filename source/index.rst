
----

About
=====

Welcome! This website corresponds to a template for building academic course 
websites using `Sphinx <https://www.sphinx-doc.org/en/master/>`_, a documentation 
generator using Python. Many of our course materials are developed using Jupyter 
notebooks, making documentation generation a great way to make them searchable without 
worrying about configuring HTML output and integration with other hosting solutions

Deployment
----------
This website is built from the `parent GitHub repository <https://github.com/gchure/course_sphinx_template>`_
using a GitHub action. In short, every time you tag a release on the parent repository, the website is 
automatically compiled and rehosted. This allows you to develop and commit changes 
to the website, without constantly recompiling. 

Usage
-----
To use this website, navigate to the `parent repository <https://github.com/gchure/course_sphinx_template>`_
and click the "Use This Template" button. Enter the desired name of your course


.. The following lines are necessary in RST to populate the side bar. In short,
   you should have each category


.. toctree::
   :maxdepth: 1
   :caption: Lessons
   :hidden:
   
   lessons/lesson_1.ipynb
   lessons/lesson_2.ipynb


.. toctree::
   :maxdepth: 1
   :caption: Syllabus & Policies

   syllabus
   policies

.. toctree::
   :maxdepth: 1
   :caption: Homeworks

   problem_sets/problem_set_1


   