# SICB2021 SlicerMorph Workshop
This is a brief introduction to 3D Slicer and the SlicerMorph extension for the Society for Integrative and Comparative Biology annual meeting. 

## [Installing 3D Slicer and SlicerMorph]
[See instructions here](https://github.com/SlicerMorph/SlicerMorph#installation)

For this workshop please download THIS version of 3D slicer for [Windos](https://download.slicer.org/bitstream/1428488), [MacOS](https://download.slicer.org/bitstream/1428525), or [Linux](https://download.slicer.org/bitstream/1429054) and then use the extention manager to install SlicerMorph. 

## Getting Started with 3D Slicer and SlicerMorph

* [Introduction to Slicer - Official Slicer Documentation](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html)
* [SlicerMorph Modules Description](https://github.com/SlicerMorph/SlicerMorph#module-descriptions)
* [SlicerMorph Preprint - detailed description of functionality of 3D Slicer and SlicerMorph](https://www.biorxiv.org/content/10.1101/2020.11.09.374926v1)
* [SlicerMorph project website with additional tutorials and events calendar](http://SlicerMorph.org)
* [SlicerMorph Github Source repository](https://github.com/SlicerMorph/SlicerMorph)

## Sample Data Links
We will mostly use datasets bundled with the SlicerMorph during the workshop. These datasets become available in the `SampleData` module of 3D Slicer after the SlicerMorph extension is installed. 

For demonstration of using MorphoSource data and segmentation examples, we will use this particular dataset: https://www.morphosource.org/concern/media/000076039?locale=en. If you do not have a MorphoSource account, please sign up. 

### 3D Slicer Basics (UI, Input/Output and Data) 
*	[Navigating UI](https://slicer.readthedocs.io/en/latest/user_guide/user_interface.html)
* [Extension Manager and Catalogue](https://slicer.readthedocs.io/en/latest/user_guide/getting_started.html#extensions)
* [Loading Data and Saving (Slicer's Default way)](https://slicer.readthedocs.io/en/latest/user_guide/data_loading_and_saving.html)
* [Data Module and Subject Hierarchy explained](https://slicer.readthedocs.io/en/latest/user_guide/modules/data.html)

### SlicerMorph Specific Functionalities for Loading and Saving Data
* [ImageStacks](https://github.com/SlicerMorph/S_2020/blob/master/Day_1/ImageStacks/ImageStacks.md)
* [ExportAs](https://github.com/SlicerMorph/S_2020/blob/master/Day_1/ExportAs/ExportAs.md)

## Visualizing and Annotating your Data using 3D Slicer Modules

*	[Volume Rendering](https://github.com/SlicerMorph/S_2020/blob/master/Day_2/VolumeRendering/VolumeRendering.md)
*	[Markups](https://github.com/SlicerMorph/S_2020/blob/master/Day_2/Markups/Markups.md)
* [Segmentations](https://github.com/SlicerMorph/S_2020/blob/master/Day_2/Segmentation/Segmentation.md)
*	[Models](https://github.com/SlicerMorph/S_2020/blob/master/Day_1/Models/Models.md) 
*	[SampleData-Volumes-CropVolume](https://github.com/SlicerMorph/S_2020/blob/master/Day_1/CropVolume/CropVolume_and_Volumes.md)
*	[Transforms](https://github.com/SlicerMorph/S_2020/blob/master/Day_1/Transforms/Transforms.md)

## SlicerMorph Morphometrics Related Modules

* [Create Semilandmark Patches](https://github.com/SlicerMorph/S_2020/blob/master/Day_3/Patch-based_semiLMs/Patch-based_semiLMs.md)
* [Pseudolandmark generator](https://github.com/SlicerMorph/S_2020/blob/master/Day_3/PseudoLMGenerator/PseudoLMGenerator.md)
* [MarkupEditor](https://github.com/SlicerMorph/S_2020/blob/master/Day_3/MarkupEditor/MarkupEditor.md)
* [ALPACA - Transfer Landmarks between Meshes](https://github.com/SlicerMorph/S_2020/blob/master/Lab_ALPACA/README.md)
*	[Generalized Procrustes Analysis (GPA)](https://github.com/SlicerMorph/S_2020/blob/master/Day_3/GPA/GPA.md)

## Solutions to Common Issues with 3D Slicer and SlicerMorph

Some of these questions frequently (and repeatedly) asked on the Slicer forum. This is a collection of answers to previous inquries which might be helpful:

### Volume Rendering 
* [**Strong staircase artifacts in Volume Rendering:**](https://discourse.slicer.org/t/volume-rendering-staircase-artifacts/14666)
* [**Low Volume Rendering perfomance and stuttering:**](https://discourse.slicer.org/t/pixelated-3d-view-in-volume-rendering/15605/6?u=muratmaga)
* [**No rendering in 3D windows in GPU rendering:**](https://discourse.slicer.org/t/hardware-suggestion-and-graphic-cards-ubuntu-or-macos/14348/6?u=muratmaga)

### Memory issues with Crop Volume, Segmentation oversampling and related
* [**Out of memory #1**](https://discourse.slicer.org/t/computer-slows-down-after-volume-is-oversampled/15743/6?u=muratmaga)
* [**Out of memory #2**:](https://discourse.slicer.org/t/limitation-in-increasing-the-resolution-in-crop-volume-module/9621/2)
* [**Bad Allocation Exception**](https://discourse.slicer.org/t/bad-allocation-exception/12172)

### Miscellaneous
* [**Why JPG is a poor format for 3D volumes:**](https://discourse.slicer.org/t/error-when-saving-labelmap-to-jpg/11630)
* [**Why STL is a poor format for distribution of 3D models:**](https://discourse.slicer.org/t/beware-of-the-stl-file-format/7642/18)
* [**Reading/Writing large volumes is slow**:](https://discourse.slicer.org/t/can-slicer-utilise-multiple-cores-on-linux/9240)
Note that is almost always tied to file compression, which is enabled by default in Slicer. If you choose to use SlicerMorph specific settings, it will disable compression. 
* [**Incorrect Z-spacing in multislice TIFF:**](https://discourse.slicer.org/t/saggital-and-coronal-view-are-distorted-stretched-out/6868)
