# angular-
### 1、$index与$parent.$index
angular的循环嵌套就是多个ng-repeat的嵌套，通过$index可以得到当前循环的索引值。如果要获得父级循环的索引值，使用$parent.$index即可。
### 2、ng-if&ng-show&ng-hide
尽可能的使用ng-if代替ng-show和ng-hide，这将大大提升网站的性能。因为ng-show和ng-hide会执行其中的绑定，而ng-if只在值为true的时候执行其中的绑定。
