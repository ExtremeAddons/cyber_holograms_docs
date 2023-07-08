.. _use_in_extreme_pbr:

Extreme PBR Expansion
========================

This section is dedicated to the use of the Cyber Holograms expansion for Extreme PBR.

If you want to use Cyber Holograms in Asset Browser go to the dedicated section: :ref:`use_in_asset_browser`



.. Note::

        Extreme PBR is distributed separately and is an addon to itself, here is the link to Extreme PBR:

        - Blender Market: https://blendermarket.com/products/extreme-pbr-addon-for-blender-279-2
        - Gumroad: https://andrew-d.gumroad.com/l/BvpHx


Youtube Tutorial
-----------------

Questo tutorial ti aiuterà a capire come usare Cyber Holograms in Extreme PBR.

.. raw:: html

        <iframe width="560" height="315" src="https://www.youtube.com/embed/kIwrdTSkDdo" title="YouTube video player"
        frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture;
        web-share" allowfullscreen style="display: block; margin: auto;"></iframe>


------------------------------------------------------------------------------------------------------------------------

Material Editor
-----------------

Each Holographic material applied with Extreme PBR will have the advantage of having a dedicated and specially
built editing interface, each material has been designed to be as simple as possible to use and at the same time
have maximum control possible from the Extreme PBR panel.

.. image:: _static/_images/extreme_pbr/material_editor_01.jpg
    :align: center
    :width: 800
    :alt: material_editor_01

------------------------------------------------------------------------------------------------------------------------

Color
******

You can change the colors and the emission strength

.. image:: _static/_images/extreme_pbr/material_editor_02.jpg
    :align: center
    :width: 800
    :alt: material_editor_02


------------------------------------------------------------------------------------------------------------------------

Blend
******

You can set the blending between the Grid and the Contour area, trim the sharpness of the blending area,
set the transparency setting of Eevee material, fade the faces with inverted normals

.. image:: _static/_images/extreme_pbr/material_editor_03.jpg
    :align: center
    :width: 800
    :alt: material_editor_03

------------------------------------------------------------------------------------------------------------------------

Modify Grid
************

You can set the scale of the grid, its thickness and rotation

.. image:: _static/_images/extreme_pbr/material_editor_03.jpg
    :align: center
    :width: 800
    :alt: material_editor_05

------------------------------------------------------------------------------------------------------------------------

Animate holograms
******************

All Hologram materials are animated by a procedural texture. Press play and trim the strength, the range, the scale and the speed of the animation

.. image:: _static/_images/extreme_pbr/material_editor_04.jpg
    :align: center
    :width: 800
    :alt: material_editor_06


The effect can be binded to Camera coordinates, UV coordinates or World coordinates


------------------------------------------------------------------------------------------------------------------------


Animated Glitch
****************

On top of texture animation you can add a Glitch effect, which will turn off some bands of the model on a random fashion
or even shut down the whole material.

- **Glc Speed (Full)** is the base value of the speed of the whole Glitch effect
- **Glc Shutting down** is the amount of the total shutdown of the material
- **Glc OSC Noise scale** is a multiplier of the overall speed
- **Glc Phase** shifts in time the noise
- **Glc Bands speed** controls the speed of bands only
- **Glc Bands Strength** controls the strength of the Bands effect
- **Glc Bands scale** sets the scale of the bands
- **Glc Bands Thickness** sets the proportions between bands and unaffected areas
- **Glc Bands distortion** adds a stretching distortion to make the bands less readable


.. image:: _static/_images/extreme_pbr/material_editor_05.jpg
    :align: center
    :width: 800
    :alt: material_editor_07









