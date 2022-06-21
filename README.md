```php
<?php

namespace Aanikid\Lotfi;

use Aanikid\Lotfi\Present;
use Aanikid\Lotfi\Abilities;
use Aanikid\Lotfi\Ambitions;
use Aanikid\Lotfi\Hobbies;

class About extends Me
{
    public function __construct()
    {
        $this->actualWork();
        $this->getSkills();
        $this->getGoals();
        $this->getHobbies();
    }

    private function actualWork()
    {
        Present::renderJob();
    }

    private function getSkills()
    {
        Abilities::renderSkills();
    }
    
    private function getGoals()
    {
        Ambitions::renderGoals();
    }
    
    private function getHobbies()
    {
        Hobbies::renderHobbies();
    }
}
```
