```c++
class Student
{
  public：
      int m_node;
      char *m_name;
      int m_age;
     void func()   //成员函数
     {
         
     }
}

int main(int argc,char*argv)
{
    Sturent aaa;
    aaa.m_node=argv[1];
    aaa.m_name=argv[2];
    aaa.m_age=arg[3];
}
```



```c++
class rectangle
{
 public:
    float m_long;
    float m_wide;
    
    rectangle(float x,float y)//先把长和宽读到对象内的属性
    {
         m_long = x;
         m_wide=y;
    };
    float get_perimeter()//求周长
    {
        return 2m_long+2m_wide;
    }
    float get_area()//求面积
    {
        return m_long*m_wide;
    }
}

int main()
{
    rectangle aaa(10,20);
    rectangle bbb(2,3);
    float C1=aaa.get_perimeter();
    float S1=aaa.get_area();
    
    float C2=bbb.get_perimeter();
    float S2=bbb.get_area();
}
```

```c++
class stack
{
    
}
```

