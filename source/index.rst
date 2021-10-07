:notoc:

*************************************************
ShuttleDrive Tetrode Drive
*************************************************

*This is the documentation site for the Open Ephys ShuttleDrive Tetrode drive, an open-source, lightweight tetrode drive for use in freely moving mice.*

.. image:: /_static/images/shuttleDrive_drawing.png
  :align: center
  :scale: 80

Key Specifications
###################

* Channel count: 16 tetrodes, up to 64 ephys channels per ShuttleDrive
* Weight: ~2g for 16 tetrode drives
* Build time:  < 1 day
* Travel distance: 4.5 mm
* Fully enclosed mechanism
* Low center of gravity
* Easy and fast to assemble
* Note that there is a design available for a 256 channel, 64 tetrode drive `here <https://github.com/open-ephys/shuttle-drive/tree/master/large_64drives>`_

The 16 tetrode implant weighs approximately 2 grams, so it can be used in freely moving mice. The small size and low center of gravity of the design also makes it possible to target off-center areas, or even to fit a drive implant under a microscope for simultaneous imaging and electrophysiology.
The flexible recording array geometry allows recordings from multiple brain areas. Individual lowering of each electrode makes it possible to hit deep and small targets. The drive is easy to build, two or three drives can be built per day even with relatively little training. It accommodates arbitrary spatial arrangements of electrodes, and is compatible with a variety of recording systems.


This design is the successor to the flexDrive, and has improved build speed, robustness, size, and drive stability and linearity. 
The documentation for the flexDrive is available :ref:`here <flexdriveoverview>`.


Getting Started
#################################################

.. raw:: html

    <div class="container">
        <div class="row">
            <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
                <a href = ../html/pages/assemblyguide.html>
                <div class="card text-center intro-card shadow" style="width: 22rem;">
                <img src="_static/images/noun_screwdriver.svg" class="card-img-top" alt="Open Ephys logo" height="160">
                <div class="card-body flex-fill">
                    <h4 class="card-title">Building a Drive</h5></a>

.. raw:: html

                </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
                <a href = ../html/partslist.html#partslist>
                <div class="card text-center intro-card shadow" style="width: 22rem;">
                <img src="_static/images/shuttledrive.svg" class="card-img-top" height="160">
                <div class="card-body flex-fill">
                    <h4 class="card-title">Using the Drive</h5></a>

.. raw:: html

                </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
                <a href = "https://iopscience.iop.org/article/10.1088/1741-2552/ab77f9">
                <div class="card text-center intro-card shadow" style="width: 22rem;">
                <img src="_static/images/paper.svg" class="card-img-top" alt="Some books" height="160">
                <div class="card-body flex-fill">
                    <h4 class="card-title">ShuttleDrive Paper</h5></a>

.. raw:: html

                </div>
                </div>
            </div>
            <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
                <a href = "https://open-ephys.org/drive-implant/drive-parts">
                <div class="card text-center intro-card shadow" style="width: 22rem;">
                <img src="_static/images/noun_macbook.svg" class="card-img-top" alt="A laptop" height="160">
                <div class="card-body flex-fill">
                    <h4 class="card-title">Buy Parts Here</h5></a>

.. raw:: html

                </div>
                </div>
            </div>
        </div>
    </div>

.. toctree::
    :hidden:
    :maxdepth: 2
    :titlesonly:

    pages/assemblyguide.rst
    pages/usingdrive.rst
