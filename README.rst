====================================
Part 2: Automated Ebook Organization
====================================
`:information_source:` 

 - This is a continuation from `part 1 <https://github.com/raul23/experiment-ebooks-classification>`_ 
   where multiple models were trained for the classification of ebooks.
 - In this second part, the best model from `part 1 <https://github.com/raul23/experiment-ebooks-classification>`_  
   will be used to automate the organization of ebooks within the filesystem by categorizing them according to their respective topics.

.. contents:: **Contents**
   :depth: 3
   :local:
   :backlinks: top

Introduction
============
In the `first part <https://github.com/raul23/experiment-ebooks-classification>`_, multiple 
classifiers were trained on three datasets of ebook text of different size. The 
classification task consisted in determining what topic each ebook belong to (e.g. algorithms, 
magnetism, statistics).

The ``SGDClassifier`` was the model that gave the `best overall performance 
<https://github.com/raul23/experiment-ebooks-classification#conclusion>`_ on the medium-size and 
large datasets. Thus ``SGDClassifier`` will be the chosen model in this second part where it will 
be used to determine where to move a given ebook within the user's filesystem based on its topic.
