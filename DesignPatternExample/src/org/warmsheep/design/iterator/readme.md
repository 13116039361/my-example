迭代器模式说明
===

优点：
---
1、简化了遍历方式   
2、可以提供多种遍历方式，我们可以根据需要提供正序遍历，倒序遍历两种迭代器，用户用起来只需要得到我们实现好的迭代器，就可以方便的对集合进行遍历了。      
3、封装性良好，用户只需要得到迭代器就可以遍历，而对于遍历算法则不用去关心     

缺点：
---
对于比较简单的遍历（像数组或者有序列表），使用迭代器方式遍历较为繁琐。    


迭代器模式的适用场景
---
我们只要实现一个集合，就需要同时提供这个集合的迭代器，就像java中的Collection，List、Set、Map等，这些集合都有自己的迭代器。    
假如我们要实现一个这样的新的容器，需要引入迭代器模式，给我们的容器实现一个迭代器。   

大多数语言在实现容器的时候都提供了迭代器，并且在大多数情况下可以满足我们的需要，所以需要我们自己去实现迭代器模式的场景还是比较少的，我们只需使用已有的容器和迭代器就可以了。