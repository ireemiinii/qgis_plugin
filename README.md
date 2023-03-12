<img src="https://scontent.fesb7-1.fna.fbcdn.net/v/t39.30808-6/239489720_512544036565949_1369849290683847873_n.jpg?_nc_cat=101&ccb=1-5&_nc_sid=09cbfe&_nc_ohc=S0DVCQIwKPAAX9EgI8K&_nc_ht=scontent.fesb7-1.fna&oh=00_AT95hb6Tm0w5zBlQTpSBC-JZ8tt3Q65GvsfxpWdTg0AFZg&oe=61D9F4D7" width="25%" height="25%">

## This repository has been created to share within the group in the final assignment for the GMT- 456 GIS Programming course. 
Group 16 consists of three people: 
  - 21732838 - Ceren Aşkit 
  - 21732881 - İrem Bakır
  - 21732857 - Dilan Ateş

To develop the Calculate Distance plugin created to be used in QGIS software and to add new features as a final homework within the scope of programming in geographic information systems (GMT-456) course.
The study was carried out in accordance with the requirements specified in the final file.
The requirements are listed below:

• Requirement 1 (RQ-1). If a point layer is selected, the plugin will identify all the pairwise distances. The plugin will then create a new line layer, consisting of two lines, and add it to the layer panel.
RQ- 1.1. The first line connects the two closest points, while the second one connects the two most distant points.
RQ- 1.2. These two lines will have their lengths stored as a field. In addition, the start and end points' IDs will be stored unless the “No

• RQ- 2. If a (poly)line layer is selected, the plugin will identify the start and end points of all lines. two fields will be added to the input layer: length, which stores the actual length of the input features; and shortest length, which stores the shortest distance between the start and end points of input features.

• RQ- 3. If a polygon layer is selected, the plugin will provide a warning that the input geometry is not supported.

Additional Requirements
• Language support
• Additional features depending on the group size.
• Always use your GitHub Repo throughout the process.
We can define the working steps of the assignment as follows:

![workflow drawio](https://user-images.githubusercontent.com/76746514/148506258-f2835b89-8d79-4196-b275-04b79f6f504c.png)


In the window that appears after the plugin is run, the input file is selected under the 'layers' heading.
According to beytepe data, the input file contains columns as id and name. It can be continued by selecting id or name, but the 'No id' option is also presented as a check box.
Then output is named and its path is given. The steps up to this point are the basic requirements of the assignment.

![noid](https://user-images.githubusercontent.com/76746514/148515267-1c93587b-9085-4eda-8e4f-a94a2b050410.png)
![id](https://user-images.githubusercontent.com/76746514/148515264-5e65cdd4-6306-49a3-9183-a91447051311.png)

The result when the 'OK' option is clicked and the plugin is run is shown below.
![noid2](https://user-images.githubusercontent.com/76746514/148515268-f2ac51c1-7352-4782-86c5-d750344016b7.png)


According to beytepe data, the input file contains columns as id and name. It can be continued by selecting id or name, but the 'No id' option is also presented as a check box.
When the 'No id' option is checked, the id's of the points do not appear in the attribute table of the output.
When this option is not checked, the id's of the points appear in the attribute table of the output.

![id2](https://user-images.githubusercontent.com/76746514/148515265-ddcb3a86-b590-4765-83f1-e0fe5a824de1.png)
![noid3](https://user-images.githubusercontent.com/76746514/148515272-6411eb2f-c4e1-49d2-a376-7ad26545864a.png)


In addition to the plugin, four new features have been added.

  1-) Change line color

  2-) Change the thickness of the line
  
  ![WhatsApp Image 2022-01-07 at 1 24 42 PM (1)](https://user-images.githubusercontent.com/76746514/148530314-5fc5dd57-c8f7-4280-ba60-cfe4792d036a.jpeg)

  ![WhatsApp Image 2022-01-07 at 1 24 42 PM](https://user-images.githubusercontent.com/76746514/148530324-f35ed4ef-38ec-41ae-95b2-327cfa1d4c0d.jpeg)

  3- )Save the output in three (3) different formats

![Ekran görüntüsü 2022-01-07 111042](https://user-images.githubusercontent.com/76746514/148515258-0c58d157-7448-49fc-90ec-9fa63d8a56dc.png)

  4-) Opening a warning window when the wrong input file is entered
  
  ![Ekran görüntüsü 2022-01-07 112142](https://user-images.githubusercontent.com/76746514/148515262-8914caeb-f4a1-4e7b-b4ea-b199d7d8aa86.png)


### Revert Back 
  - Feature1:  e199b590327a45645461bcf1939eaaadf2730888
  - Feature2:  df994c994b01db0087a4a30fb219a9d067cf4608
  - Feature3:  a7f8443340cedea06fd96a57b84b10ec3e73408f
  - Final version:  2269f6887da5461b0b515c3f0d0ebd7649bc73ce








