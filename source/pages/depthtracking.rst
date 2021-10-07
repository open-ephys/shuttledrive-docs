.. _depthtracking:

*************************************************
Electrode depth tracking
*************************************************

The 16-tetrode mouse shuttleDrive has a screw pitch of 0.15 mm/turn, and the correspondence of screw pitch to travel range is almost completely linear.

.. image:: ../../_static/images/tetrodedepth.jpg
  :align: center

The rat drive shows some scaling of the travel with a 0.205 mm/turn vs. the 0.2 mm pitch screw. Different guide tube arrangements may result in slightly different factors, so we recommend individual calibration if a very high level of precision is desired.

When the direction of travel is reversed, some hysteresis will occur. Hysteresis is measured as the amount of screw rotation after a direction reversal at which point the tetrode started moving again. See the above figure for measurements of the drive range and hysteresis of the presented drive design. In practice around 75 to 150 $\mu{\mathrm m }$ of hysteresis can be expected for the mouse drive.

These measurements are performed in air, to characterize the mechanical hysteresis of the drive mechanism itself. In the brain, another level of biological hysteresis and changes in recorded units are expected from the reaction of the tissue to tetrodes. See `Dhawale et al 2017 <https://iopscience.iop.org/article/10.1088/1741-2552/ab77f9#jneab77f9bib10>`_ for a discussion of the expected effects. The neuropil can react to tetrode implantation with a cascade of processes that include inflammatory processes with glial cell activation and eventual scar tissue formation. Even in the absence of overt immune responses, the neuropil is not static, and the position of neurons relative to tetrodes can be expected to drift over time.

Lowering electrodes
################################################

Electrodes can be lowered as soon as the animal has recovered from surgery and is nesting. Delaying the onset of the lowering for more than ~5 days post surgery increases the risk that dura and bone regrowth interferes with the electrodes. Putting the mouse in a head-post on a floating ball avoids putting any torque on the implant if the mouse tries to run/jump.

Lower one tetrode (or max. 2 tetrodes if they're at opposite ends of the array) at a time to avoid bunching. Wait >3hrs between lowering sessions to allow the brain to settle.

Try to record data during these lowering sessions and actually look at it, in e.g. simpleclust (or whatever spike sorting method you like) to check if you get units - L1 MUA can look surprisingly like units unless you look closely and sorting is the best way to know for sure when any given tetrode is in rather than just on the brain.
