# pp
A PHP Web Framework

#文档
补充中

#Examples

~~~php
##Controller
<?php

namespace mvc\controllers;

class InviteController extends \pp\Controller {
	public function doIndex() {
	  $this->view->saying = "Hello, World";
		$this->display();
	}
~~~

##View
~~~
You are saying: {$saying}
~~~
	

