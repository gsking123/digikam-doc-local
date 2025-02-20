.. meta::
   :description: digiKam Right Sidebar Filters View
   :keywords: digiKam, documentation, user manual, photo management, open source, free, learn, easy, filters, type-mime, format, labels, comment

.. metadata-placeholder

   :authors: - digiKam Team

   :license: see Credits and License page for details (https://docs.digikam.org/en/credits_license.html)

.. _filters_view:

Filters View
=============

.. contents::

The **Filters** tab is used to limit the set of images displayed in the Image Area. Normally one uses the Left Sidebar with its different views to confine the images displayed for example to the content of an album or to images with a certain label assigned to them. The **Filters** tab on the Right Sidebar offers a number of filters and if one of these are filled in, selected or checked only the cross-section of these two selections will be displayed in the Image Area.

To give an example, suppose you have a tag called *public* which tags all images except your private ones. Then you can check this *public* tag in the Right Sidebar to hide the private images (all those not having *public* tag). Whatever view mode you chose from the Left Sidebar, only *public* images will be displayed. Another typical example is the selection of a subset of tags in a hierarchical tree. Suppose you want to display *red* and *green* from a tag tree containing 7 different colors as sub-tags. Simply click on the *color* tag of the main view and check *red* and *green* from the Right Sidebar.

You can also use a combination of the filters but here we have to look a little bit closer: The main filters and also the different types of labels in the **Labels Filter** (color, pick, rating) are connected with boolean AND which means that all selected filters have to fit for the images to be displayed. If you select **JPG** in the **MIME type Filter** and *red* in the **Labels Filter** only those photographs from the selection on the Left Sidebar will be displayed that have JPG format AND are labeled *red*.

On the other hand the tags in the tag filter and the individual labels within one type of labels are connected with boolean OR as you might have noticed already in the public/private example above. That means if you check more than one tag in the **Tags Filter** all images with at least one of these tags applied will show up (as long as they are not ruled out by one of the other filters).

Another use of this tab of the Right Sidebar is drag and drop tagging. Let's say you chose with the help of the Left Sidebar a number of images to tag them and they are now displayed in the Image Area. If the tag already exists, simply drag it from the Right Sidebar onto one of the icons. A dialog will pop-up and ask if this tag should be applied to this item only, to all items or, if there is more than one icon selected (highlighted), to the selected items.

.. figure:: images/sidebar_filters_view.webp
    :alt:
    :align: center

    The Filters View From Right Sidebar

In the above example the main window shows the images from an album, the tag filter is set to 'Lieux', which reduces the set to 3 images. In the **Geolocation Filter**, we select **Images With Coordinates** which leaves only one picture from the list of items including GPS information. Then a tag is dragged from the **Tag Filter** over the icon and dropped. A pop-up dialog asks if the tag shall be applied to this item only or to all (displayed) items.

Note that the **Text Filter** has a little drop-down menu to select which image information should be included in the search and the rating group in the **Labels Filter** has one to choose whether you want a certain rating or a range.
