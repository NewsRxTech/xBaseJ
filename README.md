# xBaseJ
xBaseJ

-

This fork of xBaseJ contains explicit code to truncate the DBF file on close to the correct size.
It also contains an explicit api call to set the codepage marker value for the DBF.

These are required to be able to create DBFs that can be read by Visual Foxpro 9/Sedna without having to jump through special hoops.