CSC 143H
====

Commit Guidelines
--------------------------------------

### General

Make sure that all files follow this format: `objectName.extension`. `objectName` is the name of the object as described in your task on redmine.

### Models

Save your models as `.max` files and export to `.fbx`. Before your export do a couple of things.

1. Scale your models to 266.667% of their original size. This can be done by using the Transform Type-in tool.
2. Reset the x-forms of your model and convert to editable poly. Navigate to the last tab in your main toolbar, its icon is a hammer. At the bottom there should be a Reset X-Forms option. Press it and convert the model to an editable poly.
3. Lastly, ensure that the model is centered to the origin.

### Textures

Save your textures as `.psd` files. These files should have presevered as much of your layering as possible. Export that file as a `.tga`, as well. The `.tga` is the file we will actually be using in UDK. If your file has a normal map (which most should) save your texture as a `.dds`, as well.
