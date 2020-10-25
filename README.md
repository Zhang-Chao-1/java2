# java2
##实验目的
初步了解分析系统需求，从学生选课角度了解系统中的实体及其关系，学会定义类中的属性以及方法；
掌握面向对象的类设计方法（属性、方法）；
掌握类的继承用法，通过构造方法实例化对象；
学会使用super()，用于实例化子类；
掌握使用Object根类的toString（）方法,应用在相关对象的信息输出中。

##实验要求
.编写上述实体类以及测试主类（注意类之间继承关系的适用）
2.在测试主类中，实例化多个类实体，模拟学生选课操作、打印课程信息（信息包括：编号、课程名称、上课地点、时间、授课教师 等）；模拟学生退课操作，再打印课程信息。
3.编写实验报告。

##实验过程
import java.util.Scanner;   
public class test {
    public static void main(String[] args) {
        int flag = 1;
        courses s = null;
        while (flag == 1) {
            Scanner in = new Scanner(System.in);
            courses a = s;      //对a进行初始化赋值
            student w = new student(2019310637, "张超", 'M',a);
            System.out.println("学生信息");
            System.out.println(w);
            teacher b = new teacher(1, "王", 'M', "语文");
            teacher c = new teacher(2, "李", 'M', "数学");
            teacher d = new teacher(3, "张", 'W', "英语");
            System.out.println("教师信息");
            System.out.println(b);
            System.out.println(c);
            System.out.println(d);
            courses e = new courses("语文", 7, "101", 2, 2);
            courses f = new courses("数学", 8, "102", 2, 3);
            courses g = new courses("英语", 9, "103", 2, 4);
            
##实验感想
通过本次实验知道了面向对象具有三大特征：封装性、继承性和多态性，而面向过程没有继承性和多态性，并且面向过程的封装只是封装功能，而面向对象可以封装数据和功能。所以面向对象优势更明显。
           
        
