# EASEUP 
## Guide Docs

### Webpage Template
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


### Folders Map

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




#### Src 
Including **Classes**, **Source Files**, **DataBase(s)**, etc.

#### Script
Includes **smaller scripts** (*that use source files*) like ajax processing, etc.
