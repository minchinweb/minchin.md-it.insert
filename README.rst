Insert for Markdown-IT-Py
=========================

This is a plugin for the Python implementation of
`Markdown-IT <https://github.com/executablebooks/markdown-it-py>`_ (a CommonMark
parser) that provides insert (``<ins>``) via double pluses (``++``).

Example usage::

    >>> from markdown_it import MarkdownIt
    >>> from minchin.md_it.insert import insert_plugin
    >>> md = MarkdownIt().use(insert_plugin)
    >>> md.render("I ++added++ this")
    '<p>I <ins>added</ins> this</p>\\n'
    >>> md.render("this++text\\\\ has\\\\ spaces++")
    '<p>this<ins>text\\ has\\ spaces</ins></p>\\n'

Tests can be run using ``pytest``.

This is ported from hasgeek's Funnel, under the AGPL-3.0 license.
