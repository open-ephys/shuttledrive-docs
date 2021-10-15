*************************************************
 5 - Electrode loading
*************************************************

.. raw:: html

  <body class="theme-default aui-theme-default">
    <div id="page">
      <div id="main" class="aui-page-panel">
        <div id="main-header">
        </div>
        <div id="content" class="view">
          <div class="page-metadata">
            Created by <span class='author'> Jakob Voigts</span>, last modified on Jun 12, 2015
          </div>
          <div id="main-content" class="wiki-content group">
            <h3 id="id-5-Electrodeloading-AttachingEIBtobody">Attaching EIB to body</h3><div class="methodblock">Attach EIB to the drive body with screws and/or epoxy.<br/>At the same time, insert fiber/s through the holes in EIB.</div><div class="methodblock">If connections of electrodes to the opposing side of the EIB are desired, only glue and/or screw the EIB to the drive body on the higher side (see later step). Also, if this 'criss-cross' pattern of electrodes under the EIB is desired, consider delaying adding the fiber until after loading the electrodes. Otherwise, it will be harder to move the electrodes over to the opposite side of the EIB.<br/>Make sure to use enough epoxy to hold the EIB to the drive body securely. Ideally, the epoxy should reach down the 'ears' on the drive body a bit, and also reach around the edge of the EIB, and extend a bit onto the top of the EIB. The only constraint here is that all vias need to be clear, and access to the screws needs to be unobstructed. </div><h3 id="id-5-Electrodeloading-GluingfiberstoEIB">Gluing fibers to EIB</h3><div class="methodblock">Position fibers at desired depth, and glue them to the EIB with epoxy. <br/>Make sure to add epoxy to the top and bottom of the EIB to securely stabilize the ferrule.</div><div class="methodblock">Even if no optical fibers are used, gluing an empty 1.25mm optical ferrule or similar piece of metal into the ferrule mounting hole(s) of the EIB provides a convenient way to attach the cap later.</div><h3 id="id-5-Electrodeloading-Loadingelectrodes">Loading electrodes</h3><p><span style="color: rgb(0,0,0);">The following is a adapted standard protocol for electrode loading. </span><br/><span style="color: rgb(0,0,0);">See </span><a class="external-link" href="http://www.jove.com/video/1098/micro-drive-array-for-chronic-in-vivo-recording-tetrode-assembly" rel="nofollow">Nguyen et al. 2009</a><span style="color: rgb(0,0,0);"> for an in-depth video protocol for electrode loading.</span><br/><br/></p>
            <div class="methodblock">Load electrodes into the shuttle tubes using ceramic tipped forceps.</div>
            <div class="methodblock">Cut each electrode to the desired length with very sharp scissors according to your electrode protocol. If required, make small adjustments to electrode depth, and glue it to the top of shuttle tubes with epoxy. After epoxy is cured, connect the electrode to the EIB using gold pins and/or solder. Document the mapping of channels to drive number and electrode position.</div><p><span class="confluence-embedded-file-wrapper confluence-embedded-manual-size"><img class="confluence-embedded-image confluence-external-resource" height="244" width="400" src="http://open-ephys.github.io/flexDrive/imgs/top_assymetry.png" data-image-src="http://open-ephys.github.io/flexDrive/imgs/top_assymetry.png" loading="lazy"></span><span style="color: rgb(0,0,0);"> </span></p>
            <div class="methodblock">Make sure that there is enough slack in the electrode wire to allow for the full range of drive motion.</div><div class="methodblock">There are two main <strong>options for loading tetrodes</strong>: Straight to the nearest vias, or and across the EIB.</div>
            <div class="methodblock"><div class="methodblock"><strong>Across: </strong>In case you want to load tetrodes 'across' the EIB, the top of the drive body is asymmetric, so that the EIB stands off by ~.6mm from one side of the body when only the higher side is glued and/or screwed to the body.</div>
            <div class="methodblock">This way, electrodes can be loaded and brought around to the other side of the EIB so that the electrodes run under the EIB and are protected. We have also gotten good results from loading the electrodes to the closest vias in the EIB, but this requires a slightly higher level of care to avoid damaging the wires with the screw driver when lowering drives.</div></div>
            <div class="methodblock"><strong>Direct:</strong> Just load to the closest vias, but make sure to leave enough slack for the drive to move down without tearing the tetrode wire. Also try to make sure the tetrode wire sits under the EIB rather than looping out. It can help to *<em>very gently*</em> pull on the tetrode where it exits the shuttle tube to make sure it has a kink that directs it under the EIB. It is pretty easy to not see a tetrode wire that sticks out during lowering so its best to avoid any possibility of accidentally ripping them with the screwdriver.</div><div class="methodblock">Electrodes are typically gold-plated after the shield is attached and the drive has been almost completed. The last step after gold-plating is to secure the gold pins with a layer of epoxy.</div><h3 class="methodblock" id="id-5-Electrodeloading-Groundwire">Ground wire</h3>
            <div class="methodblock">Attach the uninsulated shield wire to the EIB with gold pins and/or solder. The wire only needs to be long enough to make good contact with the shield cone later.</div><div class="methodblock">Attach the ground wire to the EIB with gold pins and/or solder. The ground wire should extend to the bottom of the drive with enough free length to reach the desired ground site during the implant surgery. Make sure the ground wire is routed along one of the sides of the drive so that it doesn't interfere with lowering the drives later.</div><div class="methodblock">On EIBs with two connectors that have independent GND and REF connections, it might make sense to connect these together by feeding one wire through ground&amp;ref (or separate GND and REF depending on application) through the appropriate vias and soldering it. This results in two free ends to the wire, one for the shield, the other for the GND screw with minimal soldering etc.</div>
          </div>

          <div class="pageSection group">
            <div class="pageSectionHeader">
              <h2 id="attachments" class="pageSectionTitle">Attachments:</h2>
            </div>

            <div class="greybox" align="left">
              <img src="images/icons/bullet_blue.gif" height="8" width="8" alt=""/>
              <a href="attachments/950323/15597569.png">flexdrive_wiring.png</a> (image/png)
              <br/>
            </div>
          </div>


        </div>             </div>
      </div>     </body>
