# 由于低版本IE6,7,8不兼容getElementsByClassName,所以要封装自己的类名。封装的原理是先取出所有的盒子（标签），通过遍历来判断，如果className符合我们的要求，放入我们事先准备好的数组中（push）
