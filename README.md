```php
<?php

namespace lotfiAanikid;

class Apropos extends Moi
{
    public function activitéActuelle(): array
    {
        return [
            'Formation' => [
                'centre' => ' WebForce-3 ',
                'type' => ' Devellopeur Web ',
                'ville' => ' Lille ',     
            ]
        ];
    }

    public function Compétences(): array
    {
        return [
            Html::class,
            Css::class,
            Sass::class,
            TailwindCss::class,
            Bootstrap::class,
            Javascript::class,
            Jquery::class,
            Php::class,
            Sql::class,
            Symfony::class,
            Git::class,
        ];
    }

    public function ambition(): string
    {
        return 'Actuellement en recherche de stage, en partie Backend.';
    }
}
