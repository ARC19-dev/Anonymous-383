# EASEUP Guide Docs


## Quick Look
1. Webpage Templates
2. Directory Map
3. Task List
4. Classes


## 1. Webpage Templates
Here is the template of webpages.
```php

<?php 

require "cfg.php";

?>

<!DOCTYPE html>
<html lang="<?php echo $lang; ?>">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="<?php echo CSS ?>foo.css">
    <title><?php echo $title; ?></title>
</head>
<body class="<?php echo $theme; ?>">


<script src="<?php echo JS ?>foo.js"></script>
</body>
</html>

```


## 2. Directory Map

```
|-- assets
|  |
|  |-- css
|  |-- font
|  |-- img
|  |-- js
|  |-- scss
|  |-- ts
|
|
|-- backup
|  |
|  |-- DataBase
|  |-- etc.
|
|
|-- bin
|  
| 
|-- config
|  
|  
|-- docs
|  |
|  |-- documentation
|  |-- IDEA
|  |-- templates
|  |-- Repo etc.
|
|
|-- lib
|
|
|-- logs
|
|
|-- pages
|
|
|-- script
|
|
|-- src
|
|
|-- test
|
|
```




### Src 
Including **Classes**, **Source Files**, **DataBase**, **Core Processor**, **Main Functionality**, etc.

### Script
Includes **smaller scripts** (*that use source files*) like **ajax processing**, **file uploading**, etc.


## 3. Task Lists
- [ ] First Task
- [x] Second Task
- [ ] Third Task
- [ ] Stupid Task
- [x] Nice Task
- [ ] Task 3

## 4. Classes

#### Company (_or Startup_)
#### Group (Room)
<!-- #### Project -->
#### User
#### Task
#### Challenge
#### Exam (Test / Quiz)
#### Contract (_قرارداد_)
