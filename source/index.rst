.. toctree::
    :hidden:

    pages/assemblyguide.rst
    pages/usingdrive.rst
    pages/flexDrive/flexdriveoverview.rst

*************************************************
ShuttleDrive Tetrode Drive
*************************************************

*This is the documentation site for the Open Ephys ShuttleDrive Tetrode drive, an open-source, lightweight tetrode drive for use in freely moving mice.*

.. raw:: html

  <div class="row">
    <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 d-flex">
      <div class="card border-light">
        <img class="card-img-top" src="_static/images/shuttleDrive_drawing.png" alt="ShuttleDrive Tetrode Drive" style="margin: 0 auto">
        <a href="https://github.com/open-ephys/shuttle-drive" class="btn btn-primary" style="background-color:#f4d050;border-color:#f4d050; width: 180px; margin: auto">ShuttleDrive Design Files</a>
      </div>
    </div>
    <div class="col-lg-6 col-md-6 col-sm-12 col-xs-12 d-flex" style="margin-top: 0em!important">
      <div class="card border-light">
        <div class="card-body" >
          <p class="card-text">
          <h2>Key Specifications<a class="headerlink" href="#key-specifications" title="Permalink to this headline">¶</a></h2>
          <ul class="simple">
          <li><p>Channel count: 16 tetrodes, up to 64 ephys channels per ShuttleDrive</p></li>
          <li><p>Weight: ~2g for 16 tetrode drives</p></li>
          <li><p>Build time:  &lt; 1 day</p></li>
          <li><p>Travel distance: 4.5 mm</p></li>
          <li><p>Fully enclosed mechanism</p></li>
          <li><p>Low center of gravity</p></li>
          <li><p>Easy and fast to assemble</p></li>
          <li><p>Note that there is a design available for a 256 channel, 64 tetrode drive <a class="reference external" href="https://github.com/open-ephys/shuttle-drive/tree/master/large_64drives">here</a></p></li>
          </ul>
        </div>
      </div>
    </div>
  </div>


The 16 tetrode implant weighs approximately 2 grams, so it can be used in freely moving mice. The small size and low center of gravity of the design also makes it possible to target off-center areas, or even to fit a drive implant under a microscope for simultaneous imaging and electrophysiology.
The flexible recording array geometry allows recordings from multiple brain areas. Individual lowering of each electrode makes it possible to hit deep and small targets. The drive is easy to build, two or three drives can be built per day even with relatively little training. It accommodates arbitrary spatial arrangements of electrodes, and is compatible with a variety of recording systems.


This design is the successor to the flexDrive, and has improved build speed, robustness, size, and drive stability and linearity.
The documentation for the flexDrive is available :ref:`here <flexdriveoverview>`.


Getting Started
#################################################

.. raw:: html

  <div class="container">
    <div class="row">

      <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex" >
        <a href = pages/assemblyguide.html>
          <div class="card h-100 text-center intro-card shadow">
            <img src="_static/images/noun_screwdriver.svg" class="card-img-top" height="160">
            <div class="card-body flex-fill">
              <p class="card-reference">Building a Drive</p>
            </div>
          </div>
        </a>
      </div>

      <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
        <a class="card-reference" href = pages/usingdrive.html>
          <div class="card h-100 text-center intro-card shadow">
            <img src="_static/images/shuttledrive.svg" class="card-img-top" height="160">
            <div class="card-body flex-fill">
              <p class="card-reference">Using the Drive</p>
            </div>
          </div>
        </a>
      </div>

      <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
        <div class="card h-100 text-center intro-card shadow" >
          <a class="card-reference" href = "https://iopscience.iop.org/article/10.1088/1741-2552/ab77f9" target="_blank" rel="noopener noreferrer">
            <img src="_static/images/paper.svg" class="card-img-top" height="160">
            <div class="card-body flex-fill">
              <p class="card-reference">ShuttleDrive Paper <i class="fas fa-external-link-alt" style = "font-size:0.5em; vertical-align: super"></i></p>
            </div>
          </a>
        </div>
      </div>

      <div class="col-lg-3 col-md-6 col-sm-12 col-xs-12 d-flex">
        <div class="card h-100 text-center intro-card shadow">
          <a class="card-reference" href = "https://open-ephys.org/drive-implant/drive-parts" target="_blank" rel="noopener noreferrer">
            <img src="_static/images/noun_macbook.svg" class="card-img-top" height="160" >
            <div class="card-body flex-fill">
              <p class="card-reference">Buy Drive Parts <i class="fas fa-external-link-alt" style = "font-size:0.5em; vertical-align: super"></i></p>
            </div>
          </a>
        </div>
      </div>

    </div>
  </div>




License
#################################################

This work is licensed under CC BY-SA 4.0.

To view a copy of this license, visit https://creativecommons.org/licenses/by-sa/4.0/
