Customize the watermarks
========================

A watermark is a logo which superimposes previews. This device serves as a
deterrent to prevent the misuse of pictures.
By default, the watermark is a cross blocking the surface of an image with the
name of the collection.
It is possible to customize the watermarks applied on the pictures for each
collection.

The watermark file features
---------------------------

The watermark must be a JPEG file in square grey levels containing as many
pixels as the larger side of the sub-definition.

Upload the watermark file
-------------------------

The watermark is customizable for each Phraseanet collection. In Phraseanet
Admin, display the collection of the watermark to customize.
At the section **Watermark**, click on the button *Select* to upload a
customized watermark.

How is the watermark applied ?
------------------------------

The mask is applied as it as at the center of the preview (without scaling).
Make sure that the watermark stays understandable even if it is cropped on the
top, at the bottom, at the left or at the right depending on the position of the
picture (Horizontal, Vertical, Panoramic). 

It is better to have a shrinked watermark at the center of the picture, or a
pattern.

The *bright* pixels will enlighten the picture (raise its brightness) and the
*dark* ones will darken the picture. 

The neutral grey (127 or #808080) will leave the picture as it is : it is the
best colour to create the mask's background.
For the watermark patterns, the tests show that to much brightness creates
colour artefacts : it is better to use the grey scale.
The light grey scale gives better results (for example between #0c0c0c and
#f3f3f3)

Here is a watermark file example.

.. image:: ../../images/Faq-filigrane0.jpg
    :align: center

Applied to a picture, the watermark gives the following result.

.. image:: ../../images/Faq-filigrane1.jpg
    :align: center


Nota bene
---------

After updating a watermark to a customized watermark, and if there already are
media in *Phraseanet*, the cache files created by the application must be
deleted.
Use the following command :

.. code-block::bash

    find /path/to/subdefs -name 'watermark_*' -exec rm {} \;
