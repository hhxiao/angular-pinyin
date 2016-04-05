angular-pinyin
==============

An angularjs module can be used to get chinese pinyin from chinese, a modified version of Bill Lue's [JSPinyin](https://github.com/chinalu/JSPinyin) project. Mootools dependency is removed, can not make it work for some unknown reason. 

Usage
-----

	# add module dependency in your module
	angular.module('app', ['angular-pinyin'])

	# add service dependency in your controller
	angular.module('app').controller('CityCtrl', function($scope, Pinyin)
	alert(Pinyin.getFullChars('你好中国'));

License
-------

MIT License