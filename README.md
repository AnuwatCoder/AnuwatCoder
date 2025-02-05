### Hi there, I'm Anuwat Pattanachian! 👋

```php
<?php

// DataProfile class definition
class DataProfile {
    public $FullName;
    public $NickName;
    public $PlaceOfWork;
    public $JobPosition;
    public $Email;

    // Constructor to create a new DataProfile instance with default values
    public function __construct() {
        $this->FullName = "Anuwat Pattanachian";
        $this->NickName = "Wat";
        $this->PlaceOfWork = "Prince of Songkla University";
        $this->JobPosition = ["Computer Technical Officer, Professional Level"];
        $this->Email = "anuwat.pa@psu.ac.th";
    }

    // Method to greet
    public function sayHi() {
        return "Hi!";
    }
}

// Create a new instance of DataCraftsman
$me = new DataProfile();

// Call the sayHi method
echo $me->sayHi().'<br>';
echo $me->FullName.'<br>';
echo $me->NickName.'<br>';
echo $me->PlaceOfWork.'<br>';
echo $me->JobPosition.'<br>';
echo $me->Email;
?>
```

#### 📊 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=AnuwatCoder&show_icons=true&theme=radical)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AnuwatCoder&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

