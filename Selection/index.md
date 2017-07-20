---
layout: default
---

# Selecting Visual Objects with Freehand Sketches

Selection in digital image editing is the task of extracting an object embedded in an image, a task performed frequently in many digital content creation applications. A classic example of selection is in broadcast television news where blue screen matting is used to place a newscaster's image in front of background graphics. Artists creating magazine covers routinely extract people or products from photographs to remove unwanted background and compose the new images such that magazine titles appear to be occluded by the object naturally. Currently a number of commercial tools are available that aid in the process, but they either have severe limitations in their capabilities, or require very careful user guidance and control. In this project, we attempt to making selection easier and usable in a wider range of applications. We present the design of a tool for selecting objects using simple, rough freehand sketches similar to those used in normal interhuman communication. 

![](/Selection/selection_files/fig01.jpeg)

Figure 1. Example of object selection. (a) Original image, with a sketch drawn over image. (b) Selection computed is composited against a black background. (Original image by Gerald and Buff Corsi, California Academy of Science)


A sketching interface is an appropriate choice for image editing because the pen and pencil are ubiquitous tools for creating graphics, and sketch-based interaction would be very natural for use in handheld tablet computers. A typical example of the kind of sketch allowed by the selection tool we will describe is shown in figure 1(a). With the sketch shown, our selection tool was able to extract the head of the crane, as shown in figure 1(b). Despite the fairly convoluted profile of the crane's head, which consists of both sharp boundaries along the beak and complicated boundaries around the crane's crown, our selection tool needed only the simple sketch shown, which is natural and can be drawn quickly, without much skill and dexterity. We believe that this tool will enable sophisticated and high-fidelity graphical selection and manipulation operations in situations where the user may not have much time, such as during a live sports broadcast, or may not have much dextrous control, such as on a mobile handheld device, or may want to avoid the monotony and tedium of selection, without compromising the quality of the selection. 

![](/Selection/selection_files/fig03.jpeg)

Figure 2: Steps in selection algorithm.

## Results

![](/Selection/selection_files/fig07b.jpeg) | ![](/Selection/selection_files/fig07c.jpeg)
----|----
![](/Selection/selection_files/crane_1.jpeg) | ![](/Selection/selection_files/crane_5.jpeg)

------

## Collaborator

[Narendra Ahuja](http://vision.ai.illinois.edu/ahuja.html), University of Illinois at Urbana-Champaign 

## References

1.  Tan, Kar-Han; Ahuja, Narendra;  Selecting objects with freehand sketches . Computer Vision, 2001. ICCV 2001. Proceedings. Eighth IEEE International Conference on .  pp.337-344 . 2001 . [full text](/Publications/KarHanTan2001Selecting.pdf)
1.  Tan, Kar-Han; Ahuja, Narendra;  A representation of image structure and its application to object selection using freehand sketches . Computer Vision and Pattern Recognition, 2001. CVPR 2001. Proceedings of the 2001 IEEE Computer Society Conference on .  pp.II-II . 2001 . [full text](/Publications/KarHanTan2001A.pdf)

## Citation

```
@INPROCEEDINGS{ref:KarHanTan2001Selecting, 
   author={Kar-Han Tan and N. Ahuja}, 
   booktitle={Proceedings Eighth IEEE International Conference on Computer Vision. ICCV 2001}, 
   title={Selecting objects with freehand sketches}, 
   year={2001}, 
   volume={1}, 
   pages={337-344 vol.1}, 
   keywords={computer vision;image segmentation;object detection;coarse global segmentation;finer-grained segmentation;freehand sketches;image computation;image editing;interactive tool;linear approximation;object boundaries;objects selection;two-phase algorithm;user input;Computer science;Content based retrieval;Cranes;Digital images;Graphics;Handheld computers;Image retrieval;Image segmentation;Linear approximation;TV broadcasting}, 
   doi={10.1109/ICCV.2001.937538}, 
   note={\url{https://karhan-tan.github.io/Selection}}}
   
@INPROCEEDINGS{ref:KarHanTan2001A, 
   author={Kar-Han Tan and N. Ahuja}, 
   booktitle={Proceedings of the 2001 IEEE Computer Society Conference on Computer Vision and Pattern Recognition. CVPR 2001}, 
   title={A representation of image structure and its application to object selection using freehand sketches}, 
   year={2001}, 
   volume={2}, 
   pages={II-677-II-683 vol.2}, 
   keywords={edge detection;feature extraction;image representation;image segmentation;adjacency information;freehand sketches;gradual photometric transition;image segmentation;image structure representation;local intratriangle alpha channel estimation;mapping;medial axes;object boundary;object selection;simplicial decomposition;triangulation;vertices;Application software;Broadcasting;Channel estimation;Computer science;Digital images;Handheld computers;Image edge detection;Image segmentation;Photometry;Shape}, 
   doi={10.1109/CVPR.2001.991029}, 
   ISSN={1063-6919}, 
   note={\url{https://karhan-tan.github.io/Selection}}}
```
   
