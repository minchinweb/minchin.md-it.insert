.
++test++
.
<p><ins>test</ins></p>
.

.
++foo\++
.
<p>++foo++</p>
.

.
2++4 + 3++5
.
<p>2<ins>4 + 3</ins>5</p>
.

.
++foo~bar++baz++bar~foo++
.
<p><ins>foo~bar</ins>baz<ins>bar~foo</ins></p>
.

.
++\ foo\ ++
.
<p>++\ foo\ ++</p>
.

.
++foo\\\\\\\ bar++
.
<p><ins>foo\\\\ bar</ins></p>
.

.
++foo\\\\\\ bar++
.
<p><ins>foo\\\ bar</ins></p>
.

.
**++foo++ bar**
.
<p><strong><ins>foo</ins> bar</strong></p>
.

