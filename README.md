```php
<?php

namespace Josewowgame;

class About extends Josewowgame
{
    public function getCurrentWorkplace()
    {
        return [
            'workplace' => [
                'company' => 'AvaloxBE',
                'position' => 'Lead Developer'         
            ]
        ];
    }

    public function getDailyKnowledge()
    {
        return [
            Php::class,
            Javascript::class,
            Laravel::class,
            Vuejs::class,
            Angular::class,
            Java::class,
            CSharp::class,
            NodeJS::class,
        ];
    }

    public function getFutureGoal()
    {
        return 'Get my own software development company';
    }
}
```

---
