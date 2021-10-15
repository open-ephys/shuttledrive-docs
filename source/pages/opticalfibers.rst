.. _addfibers:

*************************************************
Adding Optical Fibers
*************************************************

Optical fibers can be added to the shuttleDrive. We recommend inserting the fibers after loading the electrodes, as usually some fibers extend past the drive bottom, so they would interfere with cutting the electrodes. Inserting fibers into the array through prepared openings (see section on making the guide tube array for details) is easier if the drive isn't shielded yet. If movable fibers are needed, see below for details on how to insert flexible fibers instead of electrodes.

This section assumes that you use glass fibers. Most steps will be the same for plastic fibers.

Making fiber stubs by hand
###############################################
Cut a length of fiber, and remove the plastic cladding. This is much easier done for larger pieces at once.

.. raw:: html

  <a class="external-link" href="https://www.google.com/url?sa=t&amp;rct=j&amp;q=&amp;esrc=s&amp;source=web&amp;cd=1&amp;cad=rja&amp;uact=8&amp;ved=0CB8QtwIwAA&amp;url=http%3A%2F%2Fwww.youtube.com%2Fwatch%3Fv%3DZvMpc9y_HaU&amp;ei=V46xU42IMojN8wHOpICwBg&amp;usg=AFQjCNEFUhG1f46uG_g7Luf52VWz7f-srQ&amp;sig2=O4rHAhz3_SXGgTG5A5CFyw&amp;bvm=bv.69837884,d.b2U" rel="nofollow">Video tutorial for removing plastic cladding</a> for a video tutorial

For added safety, cut a small slot or two into the bottom of the ferrule to ensure that it won't slip out of the epoxy. This is especially important for ceramic ferrules. Use a high speed cutting wheel for this.

Now glue the ferrules to the fiber. One easy process is to line up ~5 ferrules on the long fiber, add a drop of glue under each one, and then slide them over the glue.
Ferrules  have two sides, a convex and a concave one. The convex side needs to be facing the fiber patch cable, the concave side is where the longer piece of free fiber sticks out. Reversing the sides will likely  make it impossible to achieve good coupling.

Once the glue is set, cut the long piece into individual stubs above each ferrule by scoring with the diamond pen and breaking them. Make sure that the cut is not going below the ferrule face or it will be impossible to polish the fiber.

Now cut the fiber stubs to length at the 'bottom' end.

Polish the fibers.

Measure the light throughput with a stable light source and light meter. Its very important to use a light source with a fiber of the exact same NA and fiber diameter as will be used later, otherwise the measurement results can be meaningless.


Inserting fiber stubs into the guide tube array
#################################################

Cut the stub to the right length - when the bottom is at the desired position at the drive bottom, the ferrule should intersect the EIB so that a minimal length of the ferrule remains under the EIB.
If you left an opening in the guide tube array for the fiber to go through, drop the fiber through the correct hole in the EIB and try to hit the hole in the guide tube array. It can help to direct the fiber by holding it with small forceps under the EIB. Once it is in the guide tube array, push it lower till the depth is right (you can usually still adjust by a few 100 micron at this step by changing how deep the ferrule sits in the hole in the EIB) and glue the ferrule to the EIB with epoxy. Make sure to get enough epoxy both above AND below the EIB to hold the ferrule in place securely. It's pretty easy to accidentally pull out a ferrule if it's not glued properly.


Mobile optical Fibers
#################################################
If independent adjustment of the fiber depth throughout the experiment is desired, one or more small diameter fibers can be inserted in place of electrodes and can be lowered using the same mechanism. We found larger diameter fibers not sufficiently flexible for this method.

In this design, the fiber is lowered into a guide tube and glued to the shuttle. You may need to leave out neighbouring shuttles to make space for this. If desired, electrodes can be glued to the fibers at constant depth offset. In practice, we find that attaching 2 ferrules to the electrode interface board is straightforward, though in principle up to 16 fibers could be attached.

.. image:: ../_static/images/variant_moveable_fibers_example.png
  :align: center
