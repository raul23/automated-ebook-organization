===============================================
Part 2 of Experimenting with classifying ebooks
===============================================
`:information_source:` 

 - This is a continuation from `part 1 <https://github.com/raul23/ebooks-classification-part1>`_ where
   multiple models were tested in the classification of ebooks.
 - In this second part, the best model from part 1 will be used to decide where ebooks should be moved within the user's filesystem 
   based on their main topic.

.. contents:: **Contents**
   :depth: 3
   :local:
   :backlinks: top

Introduction
============
In the `first part <https://github.com/raul23/ebooks-classification-part1>`_, multiple classifiers were tested on three 
datasets of ebooks text of different size. The classification task to be accomplished consisted in determinging what 
topic each ebook belong to (e.g. algorithms, magnetism, statistics).

The ``SGDClassifier`` was the model that gave the best ...
