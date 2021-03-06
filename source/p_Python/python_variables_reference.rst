=============================
Python变量引用
=============================

- 变量命名规则

    - 命名要具有描述性。
    - 必须以字母或下划线开头，且只能是下划线、字母和数字的组合。
    - 不能使用Python的关键字，也称保留字。
    - 命名是区分大小写的。

- 赋值运算符

在编程语言中，一个等于号是赋值运算符，两个等于号才是比较运算符。

.. code-block:: python

    >>> a = 100
    >>> a
    100
    >>> b = 100
    >>> b
    100
    >>> a == b
    True
    >>> a is b
    True
    >>> a = 257
    >>> b = 257
    >>> a == b
    True
    >>> a is b
    False
    >>>

- 变量交换

.. code-block:: python

    >>> a = 10
    >>> b = 20
    >>> a
    10
    >>> b
    20
    >>> a, b = b, a
    >>> a
    20
    >>> b
    10
    >>>

