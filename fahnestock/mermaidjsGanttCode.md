//Waterfall Model
gantt
dateFormat  YYYY-MM-DD
title Waterfall Model

section Tasks
Decide on a language : des1, 2022-05-20,2022-05-28
Process Model : active, des2, 2022-05-28, 5d
Interface and Database Schema : des3, after des2, 5d
Database : des4, after des3, 5d
UI : des5, after des4, 5d
Testing and Integration : des6, after des5, 5d

//Incremental Model
gantt
dateFormat  YYYY-MM-DD
title Incremental Model

section Tasks
Decide on a language : des1, 2022-05-20,2022-05-26
Process Model : active, des2, 2022-05-26, 2d
Interface and Database Schema : des3, after des2, 3d
Database : des4, after des3, 2d
UI : des5, after des4, 2d
Testing and Integration : des6, after des5, 2d
Interface and Database Schema : des7, after des6, 3d
Database : des8, after des7, 2d
UI : des9, after des8, 2d
Testing and Integration : des10, after des9, 2d

//Integrate and Configure
gantt
dateFormat  YYYY-MM-DD
title Integrate and Configure

section Tasks
Decide on a language : des1, 2022-05-20,2022-05-26
Process Model : active, des2, 2022-05-26, 4d
Write Models : des3, after des2, 5d
Forms using the Model API : des4, after des3, 5d
Views/UI : des5, after des4, 5d
Testing : des6, after des5, 5d
       

