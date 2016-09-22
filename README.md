# pp
一个PHP快速开发框架，与传统的PHP框架不同，pp框架更关注系统环境集成、插件化和前后端交互。

#文档
补充中

#Examples

##Controller
~~~php
<?php

namespace mvc\controllers;

class InviteController extends \pp\Controller {
	public function doIndex() {
	  	$this->view->saying = "Hello, World";
		$this->display();
	}
~~~

##View
~~~php
You are saying: {$saying}
~~~
	

