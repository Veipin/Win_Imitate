#### Win_Imitate

���������������Ŀ������Imitate����ʾ��Ŀ��ImitateLib��dll��Ŀ��

������Ҫ�ô���ģ�����ͼ��̵Ĳ���ʱ�����ImitateLib�����ü��ɡ�

#### ImitateLib

��Ҫ����������̬�ࣺ

1. Keyboard
	- ģ����̵���ͨ����ʹ��Keyboard.Press(params Keys[] inputs)����
    - ģ��Ctrl��Alt��Shift�����ĸ����ʱ���ֱ������Ӧ��Ctrl��Alt��Shift����
    - ��ȷ��Ŀ��ؼ������뽹�������£�����Keyboard.InputByClipboard(string data)�������Խ�data�ַ����������ԴӼ��а�ճ������ʽ���뵽�ؼ���

2. Mouse
	- ģ������ƶ�������λ�ã�Mouse.MoveTo(x,y)
    - ģ������ƶ������λ�ã�Mouse.MoveTowards(x,y)
    - ģ��������м����Ҽ��ĵ����Mouse.LeftClick/MiddleClick/RightClick(int x = 0,int y = 0)
    - �ӵ�ǰλ�ÿ�ʼ��ק��굽����λ�ã�Mouse.DragTo(x,y)
    - �ӵ�ǰλ�ÿ�ʼ��ק��굽���λ�ã�Mouse.DragTowards(x,y)
    - ģ�������ֹ�����Mouse.WheelRoll(int towards) 
        - towards>0 Ϊ���¹�����towards�Ĵ�СΪ�����ķ�Χ
