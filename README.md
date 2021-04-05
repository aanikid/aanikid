```php
<?php

namespace lotfiAanikid;

class Apropos extends Moi
{
    public function activitéActuelle(): array
    {
        return [
            'Stage' => [
                'entreprise' => ' Dataview ',
                'type' => ' Devellopeur Web backend et frontend',
                'ville' => undefined,     
            ]
        ];
    }

    public function Compétences(): array
    {
        return [
            Html::class,
            Css::class,
            Sass::class,
            Bootstrap::class,
            Javascript::class,
            Typescript::class,
            React.js::class,
            node.js::class,
            Jquery::class,
            Php::class,
            Sql::class,
            Symfony::class,
            Git::class,
        ];
    }

    public function ambition(): string
    {
        return 'Actuellement en stage, ${Backend['node.js'] + Frontend['react.js']}.';
    }
}
