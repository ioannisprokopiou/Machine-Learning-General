# Stack Overflow Multiclass Classification

## Overview

This project uses text analysis to classify stackoverflow.com questions into multiple categories like 'javascript', 'css', 'jquery', or 'html'. We work with two main files:

    train.tsv: Questions with titles, bodies, and tags.
    test.tsv: Questions needing tags.

## Goal

Our goal is to predict multiple tags for each question in the test set, using patterns learned from the training set. The task involves exploring different methods, including binary classifications for each tag and clustering approaches, to accurately assign tags to questions.