# EASEUP 
## Guide Docs

##### Webpage Template
Here is the template of webpages.
```php

<?php 

require "cfg.php";

?>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="<?php echo CSS ?>pagename.css">
    <title><?php echo $title; ?></title>
</head>
<body class="<?php echo $theme; ?>">


<script src="<?php echo JS ?>pagescript.js"></script>
</body>
</html>

```

