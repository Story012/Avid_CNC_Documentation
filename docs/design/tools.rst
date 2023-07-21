.. _tools:

==================
Tools and Features
==================

Before selecting operations in CAM and producing GCODE, tooling and features in the desired part must be accounted for. There are several cases in which this is important:

.. rubric:: Table of Contents

.. contents:: 
    :local:

Tool Selection
--------------

Familiarity with the tools availible will facilitate your parts quality, accuracy, and reproducability. Tools that are in stock at the time of writing are shown below.

.. list-table:: CNC Tooling at time of writing
   :widths: 25 25 50
   :header-rows: 1

   * - Tool type
     - Cutter Diameter
     - Cutter Length
   * - Solid carbide square endmill
     - 1/4"
     - 3/4"
   * - V-groove cutter, 45 deg
     - 1/4"
     - 1/4"

Suppose a part has a large surface that requires facing, more on this in the ``CAM operations section``. The use of a larger tool diameter will be significantly more efficient in reducing time of the cut. This distinction could mean the difference between having a 3 hour operation or a 30 minute one depending on the tool geometry and part orientation. Another example is of counter-sinks within holes, where the V-groove cutter may not fit and results in either excess time to order a tool or last minute modifications in design. Ideally the part should have in consideration the extent of tooling availible and reasonable geometry in return.   

Machining Time
--------------

As mentioned, tooling can have a significant impact in the time it takes to machine a part. Not only will size of the same style of tools make a difference, so will the type of tool used. An endmill may not be the go-to solution for every type of cut required, perhaps a drill bit can reduce the amount of time without stressing any components.


Feauture Geometry
-----------------

Features made in CAD are not always possible to manufacture. However, specialized tools exist for making features that cannot be made conventionally. Consider operations availible in CAM and configurations of a tool to make complex cuts simple (and safe).

Accuracy
-----------------

The style of tooling does not primarily impact the quality of your part, as feeds and speeds are more prominent. Regardless, it is worth investigating the amount of flutes, helix angle, and/or other characteristics of a tool to best suit the needs of your design.


