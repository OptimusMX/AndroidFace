### 1.3 面向过程 & 面向对象

- 1.什么是面向过程 & 什么是面向对象 & 区别？

> [点击查看答案](https://blog.csdn.net/qq_33811662/article/details/80639390)

- 2.给我说说Java面向对象的特征以及讲讲你代码中凸显这些特征的经验。

> [点击查看Java面向对象的特征](https://www.cnblogs.com/guweiwei/p/6599289.html)  
> 至于讲讲代码中凸显这些特征的经验,其实说说还是很简单的，你可以将你的Base层如何封装的，说一下就是ok了。

- 3.什么是重载 & 什么是重写 & 区别.

>[点击查看答案](https://www.cnblogs.com/guweiwei/p/6288068.html)

- 4.谈谈你对this和super的认识.

> 其实这个题目是个送分题:  
> this:就是类中指向对象本身的一个特殊引用。    
> super:向自己超（父）类对象的一个指针，而这个超类指的是离自己最近的一个父类。  
> [学习请点击此链接](https://www.cnblogs.com/hasse/p/5023392.html)

### 1.4 八大基本数据类型&引用类型

- 1.说说Java中的8大基本类型 & 内存中占有的字节 & 什么是引用类型？

> [点击查看答案](https://blog.csdn.net/ClAndEllen/article/details/81543128)

- 2.什么是拆箱 & 装箱，能给我举栗子吗？

        public class CzDemo {
    
            public static void testInt(int a){
                System.out.println(a);
            }
    
            public static void testInteger(Integer a){
                System.out.println(a);
            }
    
            public static void main(String[] args){
                Integer integer = new Integer(3);
                //这里进行了拆箱，将Integer拆箱为int
                testInt(integer);
                int a = 3;
                //这里进行了装箱，将int装箱为Integer
                testInteger(a);
            }
        }


### 1.5 数组

- 1.能说说多维数组在内存上是怎么存储的吗？

>[点击查看答案](https://blog.csdn.net/ClAndEllen/article/details/81710931)