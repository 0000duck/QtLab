#����Widget��̽��

##Widget�ļ��ֱ߿�.

- frameGeometry: �������丸��(window frame)�ı߿�.
- geometry: �������Ϊ��ǰwidget�����ı߿�.
- rect: == (0, 0, width(), height()); ע����geometry������, ���Ǵ����Ͻǿ�ʼ�ı߿�.
```cpp
geometry().width() == width();
geometry().height() == height();
```
��ʾ��ͼ����ͼ��ʾ:

![image](https://cloud.githubusercontent.com/assets/1147451/4418117/01f0ba80-455c-11e4-87f2-13fed4328e77.png)

- contentRect: ��Ե�ڲ��ı߿�, ��geometry���ڲ�.
- normalGeometry: ���ָ���ǵ�ǰwidget�����������(**û����󻯻�ȫ��**)�ı߿�.
- childrenRect: ��ȡ**��widget**�ı߿�, ���û�к���, �����Ϊ0.