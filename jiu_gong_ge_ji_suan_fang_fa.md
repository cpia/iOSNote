# 九宫格计算方法


- 在九宫格中计算行与列的方法

```objc
//count:总个数
//columnNum：列数
  for(int i = 0;i < count;i++)
  {
    //当前item的行与列
     int row = i / columnNum;
     int col = i % columnNum;
  }
```
