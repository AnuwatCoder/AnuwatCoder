### Hi there, I'm Anuwat Pattanachian! 👋

```php
<?php
use Illuminate\Support\Facades\Route;

Route::get('/profile', function () {
    class DataProfile {
        public string $fullName;
        public string $nickName;
        public string $placeOfWork;
        public array $jobPosition;
        public string $email;

        public function __construct() {
            $this->fullName = 'Anuwat Pattanachian';
            $this->nickName = 'Wat';
            $this->placeOfWork = 'Prince of Songkla University';
            $this->jobPosition = ['Computer Technical Officer, Professional Level'];
            $this->email = 'anuwat.pa@psu.ac.th';
        }

        public function sayHi(): string {
            return 'Hi!';
        }

        public function toHtml(): string {
            return $this->sayHi() . '<br>' .
                   $this->fullName . '<br>' .
                   $this->nickName . '<br>' .
                   $this->placeOfWork . '<br>' .
                   implode(', ', $this->jobPosition) . '<br>' .
                   $this->email;
        }
    }

    $me = new DataProfile();
    return $me->toHtml();
});

?>
```

#### 📊 GitHub Stats
![Your GitHub stats](https://github-readme-stats.vercel.app/api?username=AnuwatCoder&show_icons=true&theme=radical)

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=AnuwatCoder&layout=compact)](https://github.com/anuraghazra/github-readme-stats)

