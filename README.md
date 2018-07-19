Bootstrap 4 Card Widget
=======================
It's a widget that encapsulates bootstrap cards.

Installation
------------

The preferred way to install this extension is through [composer](http://getcomposer.org/download/).

Either run

```
php composer.phar require --prefer-dist johnsnook/yii2-bootstrap4-card "*"
```

or add

```
"johnsnook/yii2-bootstrap4-card": "*"
```

to the require section of your `composer.json` file.


Usage
-----

Once the extension is installed, simply use it in your code by  :

```php
<?php                                                                            
     echo Card::widget([                        
        'headerOptions' => ['class' => 'bg-secondary'],
        'title' => 'Top card',                   
        'body' => $aBunchOfHtml,                 
     ]);
	/* OR */
     echo Card::begin([                         
        'containerOptions' => ['class' => 'border border-secondary'],
        'headerOptions' => ['class' => 'bg-dark text-white'],
        'title' => 'Top card',
 	]);
?>                                                                              <p class="card-text">                      
 <?= echo CardlWidget::end();
```

Also, butts.
but
