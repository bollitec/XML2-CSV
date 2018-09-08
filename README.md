# XML2-CSV
Converts XML to and from CSV (Excel Support)

Idea is an hierarchy based python script to transfer XML to a column model with hierarchy as "." separated header. So the transfer back to XML is possible. Positive, you have all data in one sheet.

Try to make it happens,
Jörg


Example:
&lt;toplevel&gt;
  &lt;sublevel1&gt;
    &lt;value&gt;ABC&lt;/value&gt;
  &lt;/sublevel1&gt;
  &lt;sublevel2&gt;
    &lt;value&gt;DEF&lt;/value&gt;
  &lt;/sublevel2&gt;
&lt;/toplevel&gt;

will be transferred to

toplevel.sublevel1.value  toplevel.subleve2.value
ABC                       DEF

;-)
