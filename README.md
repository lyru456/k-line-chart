##蜡烛图数据
![image](https://github.com/user-attachments/assets/20cabb00-48be-4eb0-9ea7-b96bd49c012b)

在series里定义，通过设置itemStyle改变颜色

![image](https://github.com/user-attachments/assets/7b935ca5-378c-4273-b40d-04de24018cf5)

##x轴的值
![image](https://github.com/user-attachments/assets/46552a58-1ed6-446a-82ee-55b6f410b512)
在xAxis里定义，第一组是蜡烛图的，第二组是柱状图的。
data 接受字符串数组。要把日期改成时间，原先['2023-1-1','2024-1-1',...] 的数组值换成 ['4 Jan 14:00 ','4 Jan 15:00',...]
![image](https://github.com/user-attachments/assets/bd219d75-4022-47b7-939a-798f71b724ba)


##柱状图数据
![image](https://github.com/user-attachments/assets/bef47414-2ae9-43cc-9101-09263bdfb67f)
在series里可以改变数据和颜色
![image](https://github.com/user-attachments/assets/5b039ae7-c40d-4c80-8bc6-451e32d2905c)

##k线
![image](https://github.com/user-attachments/assets/fdbdb848-e467-4d4a-a478-91f22a0e1c0f)
在markLine里面定义
![image](https://github.com/user-attachments/assets/7abdf301-50e8-4168-854b-8d56e5bc8833)
一组为一条线，第一个对象为起点，第二个对象为终点。根据coord设置['x轴的值','y轴的值'],如果输入的值不存在，图表会变成空白
![image](https://github.com/user-attachments/assets/26f64878-9522-4ed2-8278-fea6b42521f4)
