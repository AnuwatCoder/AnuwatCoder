### Hi there, I'm Anuwat Pattanachian! 👋

```php
<?php

// DataCraftsman class definition
class DataCraftsman {
    public $name;
    public $pronouns;
    public $currentRole;
    public $passions;

    // Constructor to create a new DataCraftsman instance with default values
    public function __construct() {
        $this->FullName = "Anuwat Pattanachian";
        $this->nickname = "Wat";
        $this->PlaceOfWork = "Prince of Songkla University";
        $this->JobPosition = ["Computer Technical Officer, Professional Level"];
        $this->Email = "anuwat.pa@psu.ac.th";
    }

    // Method to greet
    public function sayHi() {
        return "Hi!";
    }
}
```

// Create a new instance of DataCraftsman
$me = new DataCraftsman();

// Call the sayHi method
echo $me->sayHi();

?>

#### 📊 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=AnuwatCoder&show_icons=true&theme=radical)

