Please Note!!

For the navbar to collapse, change the following:

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

The <button> data-target must instead include an id attribute.

WRONG 
<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="navbar-ex1-collapse">

RIGHT
<button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#navbar-ex1-collapse">

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////

In this <div> take the "navbar-ex1-collapse" out of the class attribute and make an id attribute instead.

WRONG
<div class="collapse navbar-collapse navbar-ex1-collapse">

RIGHT
<div class="collapse navbar-collapse" id="navbar-ex1-collapse">

////////////////////////////////////////////////////////////////////////////////////////////////////////////////////////
