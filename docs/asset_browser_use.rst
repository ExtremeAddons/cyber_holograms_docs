.. _use_in_asset_browser:

Asset Browser Library
========================


This section is dedicated to the use of the Asset Browser version of Cyber Holograms, if you want to use the version
for Extreme PBR, go to the dedicated section here: :ref:`use_in_extreme_pbr`


Open an Asset Browser
-----------------------

.. image:: _static/_images/installation/asset_browser_area_01.jpg
    :align: center
    :width: 800
    :alt: asset_browser_area_01

------------------------------------------------------------------------------------------------------------------------

**Select Cyber Assets from the list**

.. image:: _static/_images/installation/select_cyber_hologram_asset.jpg
    :align: center
    :width: 800
    :alt: select_cyber_hologram_assets

------------------------------------------------------------------------------------------------------------------------

**The library is divided into four sections: Materials Holograms, material Lights, Node groups Holograms and Node Groups Lights**

.. image:: _static/_images/installation/cyber_hologram_categories_example_01.jpg
    :align: center
    :width: 800
    :alt: cyber_hologram_categories_example_01


------------------------------------------------------------------------------------------------------------------------

Apply Hologram material
----------------------------

Select the Materials Holograms section and simply drag and drop an Hologram material onto your model.
The material active on the model will be automatically replaced with the Hologram material

.. image:: _static/_images/asset_browser/apply_material_from_asset_browser_01.jpg
    :align: center
    :width: 800
    :alt: apply_material_from_asset_browser_01

------------------------------------------------------------------------------------------------------------------------


Edit Hologram material
----------------------------

Once the material has been applied you can edit its parameters like any other material,
to do this, select the material and go to the "Material Properties" tab and you will find all the controls for
customize the effect


.. image:: _static/_images/asset_browser/edit_material_asb_01.jpg
    :align: center
    :width: 800
    :alt: edit_material_asb_01


------------------------------------------------------------------------------------------------------------------------


Color & Emission
---------------------

Every material has its own parameters. In this example you can define the colors of both hexagonal grid and contour,
and set the **Emission strength**


.. Note::

    In the Eevee render engine the material does not illuminate the scene, this is a limitation of Eevee.
    The material will actually illuminate the scene only in the Cycles render engine


.. image:: _static/_images/asset_browser/emission_and_color_asb_01.jpg
    :align: center
    :width: 800
    :alt: emission_and_color_asb_01

------------------------------------------------------------------------------------------------------------------------

Blend Effect
---------------------

Three sliders control the blend between the two colors. Set **Blend F min** and **Blend F max** values close each other
in order to get a sharp transition.


.. image:: _static/_images/asset_browser/f_min_f_max_asb_01.jpg
    :align: center
    :width: 800
    :alt: f_min_f_max_asb_01

------------------------------------------------------------------------------------------------------------------------

Transparency
---------------------

You can control the transparency of the hologram material, the transparency of the backface, the scale, thickness and rotation of the grid


.. image:: _static/_images/asset_browser/transparent_asb_01.jpg
    :align: center
    :width: 800
    :alt: transparent_asb_01

------------------------------------------------------------------------------------------------------------------------

Noise
---------------------


.. Note::

    The noise texture is animated, press play in the timeline in order to see the effect

You can define the strength of the noise animation, its range of action (proportion between affected and unaffected areas),
its scale and its animation speed

.. image:: _static/_images/asset_browser/noise_asb_01.jpg
    :align: center
    :width: 800
    :alt: noise_asb_01

------------------------------------------------------------------------------------------------------------------------

Change Coordinates
---------------------

The material can be anchored to Camera, UV or World Coordinates, instead of default Generated Local Coordinates.

.. image:: _static/_images/asset_browser/camera_coordinate_asb_01.jpg
    :align: center
    :width: 800
    :alt: camera_coordinate_asb_01






















