# test_name_conflict
This repo serves as a test of name conflicts in MOC. 

The Pandas library has an `inspect` method. The ModelOp runtime uses pandas to load data.

A conflict arises when the source code itself is names `inspect.py`. Python does not now which `inspect` is the right `inspect`.
