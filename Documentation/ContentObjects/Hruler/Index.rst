.. ==================================================
.. FOR YOUR INFORMATION
.. --------------------------------------------------
.. -*- coding: utf-8 -*- with BOM.

.. include:: ../../Includes.txt


.. _cobj-hruler:

HRULER
^^^^^^

This object inserts a table tag, which you can use as a horizontal
divider.

.. ### BEGIN~OF~TABLE ###

.. container:: table-row

   Property
         lineThickness

   Data type
         integer /:ref:`stdWrap <stdwrap>`

   Description
         Range: 1-50

   Default
         1


.. container:: table-row

   Property
         lineColor

   Data type
         HTML-color /:ref:`stdWrap <stdwrap>`

   Description
         The color of the ruler.

   Default
         black


.. container:: table-row

   Property
         spaceLeft

   Data type
         :ref:`pixels <data-type-pixels>` /:ref:`stdWrap <stdwrap>`

   Description
         Space before the line (to the left).


.. container:: table-row

   Property
         spaceRight

   Data type
         :ref:`pixels <data-type-pixels>` /:ref:`stdWrap <stdwrap>`

   Description
         Space after the line (to the right).


.. container:: table-row

   Property
         tableWidth

   Data type
         string /:ref:`stdWrap <stdwrap>`

   Description
         Width of the ruler ("width" attribute in the table).

   Default
         99%


.. container:: table-row

   Property
         stdWrap

   Data type
         :ref:`->stdWrap <stdwrap>`


.. ###### END~OF~TABLE ######

[tsref:(cObject).HRULER]

