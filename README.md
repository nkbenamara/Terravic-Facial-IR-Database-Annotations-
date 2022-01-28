# Terravic-Facial-IR-Database-Annotations-

## Terravic Facial IR Database

Terravic Facial IR Database is a public Thermal Face Database, available for the scientific community. It provides a set of 21676 thermal face images, gathered from 20 different subjects, under different scenarios (normal posture, wearing sunglasses/hats, indoor/outdoor and variations in pose). 

This dataset is built by Roland Miezianko and available from the following download link (http://vcipl-okstate.org/pbvs/bench/Data/04/download.html)

## Our Manual Terravic DB Annotations

This repository includes our manual annotations in VOC Format related to the Terravic Facial IR Database. 
These annotations have been generated using LabelImg (https://github.com/tzutalin/labelImg) and aim to provide sufficient data to train deep face detectors in Thermal (LWIR) imagery.

You'll find below some samples with the bounding boxes and the generated XML file using LabelImg. 

### Images with Bounding Box

Face 12|Face 13|Face 17|Face 19
:-------------------------:|:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/nkbenamara/Terravic-Facial-IR-Database-Annotations-/blob/master/annotated_face12.jpg?raw=true)  |  ![](https://github.com/nkbenamara/Terravic-Facial-IR-Database-Annotations-/blob/master/annotated_face13.jpg)|  ![](https://github.com/nkbenamara/Terravic-Facial-IR-Database-Annotations-/blob/master/annotated_face13.jpg)|  ![](https://github.com/nkbenamara/Terravic-Facial-IR-Database-Annotations-/blob/master/annotated_face13.jpg)

### XML PASCAL VOC
First annotation of the 12th face from Terravic Face Database
 
      
```xml
     <annotation>
        <folder>face12</folder>
        <filename>0001.jpg</filename>
        <path>/home/benamara/Desktop/Python Projects/db/Terravic Facial Infrared Database/face12/0001.jpg</path>
        <source>
          <database>Unknown</database>
        </source>
        <size>
          <width>320</width>
          <height>240</height>
          <depth>1</depth>
        </size>
        <segmented>0</segmented>
        <object>
          <name>thermal_face</name>
          <pose>Unspecified</pose>
          <truncated>0</truncated>
          <difficult>0</difficult>
          <bndbox>
            <xmin>103</xmin>
            <ymin>20</ymin>
            <xmax>224</xmax>
            <ymax>194</ymax>
          </bndbox>
        </object>
      </annotation>
```

## Our Paper
If you use our annotations for your research, please cite our paper.

N. K. Benamara, E. Zigh, T. B. Stambouli, M. Keche. Towards a Robust Thermal-Visible Heterogeneous Face Recognition Approach Based on a Cycle Generative Adversarial Network, International Journal of Interactive Multimedia and Artificial Intelligence, (2021), http://dx.doi.org/10.9781/ijimai.2021.12.003

