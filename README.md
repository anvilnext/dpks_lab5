# dpks_lab5
This is a repository for Laboratory Work #5 for DPKS.

"<b>lab5</b>" contains files for both Basic and Advanced tasks.

The param to check how lab works is "<b>hpar</b>". To test it, use "insmod hello.ko hpar=0", where 0 is the specified value. The output for different values:<br>
&nbsp;&nbsp;&nbsp;&nbsp;• <b>0, 5-10</b> - "Warning, continuing.."<br>
&nbsp;&nbsp;&nbsp;&nbsp;• <b>1-4</b> - "Hello, world!" printed that number of times that you've specified.<br>
&nbsp;&nbsp;&nbsp;&nbsp;• <b>>10</b> - "Error, exiting.."<br>

Also the module is allocating and freeing memory for output, so if you specified value 1 to 4, you will see how the memory is freeing from each event.
