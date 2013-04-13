====Melanders Drag and Drop Component Suite For Delphi====

The Drag and Drop Component Suite is a freeware VCL component library that enables your Delphi and C++Builder applications to support COM based drag and drop and integrate with the Windows clipboard.

The drag and drop system that is built into the VCL, is limited in that it only supports drag and drop within the same application. If you need to drag data from your application to other applications (e.g. Word, Explorer or Outlook), or if you need to be able to accept data dropped from other application (e.g. the Explorer), you have to use COM based drag and drop. COM based drag and drop is an integral and very important part of the Windows user interface and the Drag and Drop Component Suite makes it very easy to leverage all the features of COM based drag and drop in your own Delphi and C++Builder applications.

Every drag and drop operation involves two objects: A drop source and a drop target. The drop source provides the data to be dragged, and the drop target accepts the dragged data.
Likewise there are basically two sets of components in the Drag and Drop Component Suite; Drop source components and drop target components. Most of the source and target components are specialized to handle just one type of data, but a few of the components supports a wider range of data types or are completely generic.

In addition to the drag and drop components, the Drag and Drop Component Suite also includes components that can be used to build Windows Shell Extensions. While these components aren’t all related to Drag and Drop, they benefit from the Drag and Drop Component Suite framework and allow you to write Windows Shell Extensions with very little code.


====About the Github Repository====

Melanders Drag and Drop components work very well with older versions of Delphi. The components haven't officially been updated to work with the newer unicode enabled versions of Delphi and don't work out of the box. For whatever reason Anders Melander has stopped maintaining the components. (I hope Anders is well.)

The repository has been created here to distribute a modified version of the components that work with unicode Delphi versions. This repository is not being maintained Anders Melander. 

====Project Goals====
1. Maintain the components so that they continue to work in up to date Delphi versions. 
2. Write some expanded documentation.
