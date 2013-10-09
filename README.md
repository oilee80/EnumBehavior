EnumBehavior
============

Enumerable Behavior using the key as the value stored

How to Install
--------------

Add this to *app/Config/bootstrap.php*

> CakePlugin::load('EnumBehavior');

How to Use
----------

In your model

> public $actsAs = array(
> 	'field' => array(
> 		'DBValue' => 'Display Value'
> 	)
> );

Get Enum Values
---------------

From your Controller

> $this->Model->enumValues('field');

