===========================
How to flash the android OS
===========================
flash os just like the `gentoo`. *mbr* is like the *bootloader*. fastboot just like *partition tool*  and `dd`.

use the nvlash
--------------

use fastboot 
------------
#. boot into the recover code::
   
   $ adb reboot bootloader

#. unlock the bootloader (optional)::
   
   $ fastboot oem unlock
   $ //oparate following the instruction on the screen

#. flash the os image::

   $ fastboot flash system system.img 


Tips for TN7
------------
+-----+---------------+
|  gp |   google play |
+-----+---------------+
|  np |no google play |
+-----+---------------+

loren is  ipsum [Ref]_ dolor sit smet.

.. [Ref] Book or article reference.

.. seealso::

   Module :py:mod: `zipfile`
     Documentation of the :py:mod:`zipfile` standard module.

.. code-block:: python 
   :emphasize-lines: 3,5

   def some_function():
        interesting= False
        print 'This line is highlited.'
        print 'this line is not'
        print '..but this one is'
