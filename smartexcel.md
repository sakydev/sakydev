# Project SmartExcel
![PHP](https://img.shields.io/badge/PHP-777BB4?logo=php&logoColor=white) ![Laravel](https://img.shields.io/badge/Laravel-FF2D20?logo=laravel&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white) ![PhpSpreadsheet](https://img.shields.io/badge/PhpSpreadsheet-00AEEF?logo=php&logoColor=white)

### Why
PlanA Gmbh, a carbon accounting company has several clients. These clients come with different data structures and processes. The difficulty of adapting to all different models isn't helped further by common human errors. We started with hardcoded hand-crafted templates but that solution was quickly impossible with scale.

### What
SmartExcel was a tool for the briding gap between customers and data. It allowed customers to define hundreds of parameters and set conditions for modifications. These configurations then reflected across their data imports and exports. They could upload CSV, XLS or XLSX formats and we converted their data according to specified formats. The same process took place for exports.

### How
PHP & Laravel were core powers underneath the feature. The heavy lifting of manipulating and processing files was handled by [PHPSpreadSheet](https://github.com/PHPOffice/PhpSpreadsheet). Eventually, our solution enabled in-file warnings, restrictions and limitations, conditional logic, and more. All dynamically changing based on client configurations, of course. 
