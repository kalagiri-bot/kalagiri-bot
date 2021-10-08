```php
<?php

namespace krishnakanth_bot;

class About extends Bot
{
    public function getCurrentWorkplace(): array
    {
        return [
            'owner' => [
                'name' => 'Krishnakanth Alagiri',
                'githubProfile' => 'bearlike',
                'url' => 'https://thekrishna.in/'
            ]
        ];
    }
}
```
