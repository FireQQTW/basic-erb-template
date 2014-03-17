Fire.app ERB template
=====================
---------------------------------------
this is my basic fire.app's ERB Template, you can use Fire.app watch the project, thanks.

###1. Limit the maximum width
you can edit the `$basicWIdth_Desktop` of the scss file `main.scss` to control the page maximum width.

If you don't use the full-width structure, you can delete `_index_tmpSet_full.html.erb` and `_layout_full.html.erb`.


###2. Screen width is the maximum width
If you need the maximum width of the website according to the screen, delete `_index_tmpSet.html.erb` and `_layout.html.erb`, then change the name of `_index_tmpSet_full.html.erb` and `_layout_full.html.erb`.

    _index_tmpSet_full.html.erb  --->   _index_tmpSet.html.erb
    _layout_full.html.erb        --->   _layout.html.erb