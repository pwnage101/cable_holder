This is a CAD model for a chain keeper for 1x drivetrains.  The stl meshes are
included for your convenience, but the source file is provided if you need to
make any modifications (e.g. to change the seatpost diameter, number of
chainring teeth, etc.).  It is nearly fully parametric, and that will improve
as I make more of them for different bikes.

I've 3D printed the included stl meshes, and installed it on my bike:

.. image:: photo.jpg
   :scale: 50 %

Instructions
------------

To edit the model and/or create new meshes, you need FreeCAD version 0.16 or
later:

http://freecadweb.org/

The parameters for the model are defined in the spreadsheet contained in the
.fcstd file.  These are more or less the parameters that you can change:

+-----------------+---------------+---------+------------------------------------------------------------------------------+
| name            | current value | units   | description                                                                  |
+=================+===============+=========+==============================================================================+
| seat angle      |          72   | degrees | angle of the seat tube relative to the ground                                |
+-----------------+---------------+---------+------------------------------------------------------------------------------+
| seat diam       |          31.8 | mm      | diameter of the seat tube, most likely one of: 28.6, 31.8                    |
+-----------------+---------------+---------+------------------------------------------------------------------------------+
| chain width     |           6.8 | mm      | width across two outer links of the chain.  6.8 is used for a 9 speed chain. |
+-----------------+---------------+---------+------------------------------------------------------------------------------+
| chain link diam |           8.7 | mm      | diameter or height of the outer link of a chain                              |
+-----------------+---------------+---------+------------------------------------------------------------------------------+
| teeth           |          40   | n/a     | number of chainring teeth                                                    |
+-----------------+---------------+---------+------------------------------------------------------------------------------+

Other values in the spreadsheet should not be changed.

License
-------

This design is copyright Troy Sankey <sankeytms at gmail dot com> under the GNU
GPLv3 (see COPYING.txt).
