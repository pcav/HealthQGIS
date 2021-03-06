First steps with QGIS
=========================

We have created a first simple project so you can explore and make some practice with QGIS.

First of all, load the project.

You can do it in two different ways:

1. simply double click on the project file. In this specific case, the file **sri_lanka.qgs**. This way QGIS opens and loads automatically the project with all the layers and customizations


2. open QGIS by double clicking on the Desktop shortcut then click on **Open...** in the **Project** menu or click on the folder icon in the menu bar. Browse for the file **sri_lanka.qgs**

.. figure:: img/first_steps_1.png
	:align: center
	:scale: 80%

When the project has been loaded you will see some changes in the graphical interface of QGIS. It is divided in **5 main areas**:



.. figure:: img/first_steps_2.png
	:align: center
	:scale: 80%


in particular:

1. **Menu bar**
2. **Toolbar**
3. **Map legend**
4. **Map view**
5. **Overview**


Menu bar
---------------------

The menu bar provides access to various QGIS features using a standard hierarchical menu.

Toolbar
------------------

The toolbar provides access to several tools for interacting with the map such as: pan - zoom the map, select features, load new layers, label the layer...

Each toolbar item has popup help available. Hold your mouse over the item and a short description of the tool’s purpose will be displayed.

Every menubar can be moved around according to your needs. Additionally, every menubar can be switched off using your right mouse button context menu holding the mouse over the toolbars.


Map legend
--------------------------

The map legend area lists all the layers in the project. The checkbox in each legend entry can be used to show or hide the layer.

A layer can be selected and dragged up or down in the legend to change the z-ordering. Z-ordering means that layers listed nearer the top of the legend are drawn over layers listed lower down in the legend.

Layers in the legend window can be organized into **Groups**:

* Right click in the legend window and choose **Add Group**. Type in a name for the group and press Enter. Now click on an existing layer and drag it onto the group (in the example project provided, there are two groups: the first contains *human* infrastructures while the second contains all the *natural* layers).

Map view
----------------------
All the maps are displayed in this area. The map displayed in this window depend on the layers you have chosen to load (whether the checkbox for the layer is activated or not).
The map view can be panned (shifting the focus of the map display to another region) and zoomed in and out thanks to the toolbar buttons.

.. figure:: img/first_steps_3.png
	:align: center
	:scale: 80%

Overview
-----------
This small window shows a picture of the whole world. What is displayed in the **Map view** has a red border in the overview window: you can pan this red rectangle in order to move the map view area. Otherwise the Overview is automatically updated when you pan the map.
	
