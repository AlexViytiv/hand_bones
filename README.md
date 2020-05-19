## Human hand bones X-Ray database

Database strcuture corresponds to human hand bones naming convention.
Human hand is built of 3 major parts: 
* carpal
* metacarpal
* phalanx

Each part of human hand also can be divided into several subcategories.

Each folder has ```meta.json``` file that contains information about type of information inside folder, its name, description and list of subitems.

There are 3 types of folders:
* global - located in root of database, contains information about database.
* package - located in every transition folder, contains information about folder content.
* resources - located in leaf folders, contain information about end files with data.

