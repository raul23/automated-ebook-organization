===============================================
Part 2 of Experimenting with classifying ebooks
===============================================
`:information_source:` 

 - This is a continuation from `part 1 <https://github.com/raul23/ebooks-classification-part1>`_ where
   multiple models were tested for the classification of ebooks.
 - In this second part, the best model from part 1 will be used to decide where ebooks should be moved within the user's filesystem 
   based on their main topic.

.. contents:: **Contents**
   :depth: 3
   :local:
   :backlinks: top

Introduction
============
In the `first part <https://github.com/raul23/ebooks-classification-part1>`_, multiple classifiers were tested on three 
datasets of ebook text of different size. The classification task consisted in determining what 
topic each ebook belong to (e.g. algorithms, magnetism, statistics).

The ``SGDClassifier`` was the model that gave the best overall performance on the medium and large datasets. Thus
``SGDClassifier`` will be the chosen model in this second part where it will be used to determine where to move a
given ebook within the user's filesystem based on its topic.
