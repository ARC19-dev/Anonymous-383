# EASEUP Guide Docs


## Quick Look
* [CSS Rules](#css-rules)
* [CSS CDN](#css-cdn)
* [IMG Naming Standards](#img-naming-standards)
* [Webpage Templates](#webpage-templates)
* [Directory Map](#directory-map)
* [Task Lists](#task-lists)
* [Classes](#classes)


## CSS Rules 

### Media Queries
The following media queries must be defined. also you can define your own media queries too.
```css
@media only screen and (max-width: 1600px) {} // Optional

@media only screen and (max-width: 1200px) {}
@media only screen and (max-width: 992px) {}
@media only screen and (max-width: 768px) {}
@media only screen and (max-width: 600px) {}

@media only screen and (max-width: 400px) {} // Optional
```

### Naming Standard
use the first class name not the second one or others
```css
.class-name {
    property: value;
    true: true;
} 

.ClassName {
    False: Wrong;
}

.class_name {
    Incorrect: Unacceptable;
}
```

### CSS CDN 
There is a cdn for core css `https://easeup.ir/assets/css/core.css`

#### HTML
You can use in your **HTML**
```html
<link rel="stylesheet" href="https://easeup.ir/assets/css/core.css">
```
_**or**_

#### CSS
use in your **CSS**
```css
@import url("https://easeup.ir/assets/css/core.css");
```

## IMG Naming Standards
```html
<image-name>.<format>

setting.jpg         ACCEPTED
user-profile.png    ACCEPTED

user_profile.jpg    NOT ACCEPTED
userProject.png     NOT ACCEPTED
uSeR_pR$oF*i@e.jpg  =\
```


## Webpage Templates
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


## Directory Map

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


## Task Lists
- [ ] Clear (log)
- [ ] Log in the tag
- [ ] print_r (log with detail)
- [ ] Classes

<!-- #classes
# classes -->
## Classes

#### Company (_or Startup or Server_)
#### Group (Room)
<!-- #### Project -->
#### User
#### Chat (PV / Group chat)
#### Task
#### Challenge
#### Exam (Test / Quiz)
#### Contract (_قرارداد_)
#### Question (_بخش کافه_)
###### Roundtable (_میز گرد_)

