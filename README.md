# Lem-in

��� ������:
```bash
git clone https://github.com/Bharbo/Lem-in.git && cd Lem-in && make
```

## ��� ������������:
- ./lem-in < map
"�����������" ����� ����� � 'Lem-in/checker'

## ��������

��������� ��������� ��������� ���� ����������, ��������� �� ������ � ��������. ��� ������� ��������� � ����� �������. �� ����� �������� ��� ��� ������� �����.
���������� �������� ����� �������:
```
15                <-  ���������� ��������
3 100 500         <-  ��� �������, X-����������, Y-����������
##start           <-  ��������� �������
start 200 300
##end             <-  ����� �� �����������
end 250 900
4 100 700
1 200 500
2 200 700
5 300 500
6 300 700
start-1           <-  ������� "start" ��������� � �������� "1", � �.�.
3-4               
2-4
1-5
6-5
end-6
1-2
2-end
3-start
```

����������� �������� ����������� ������ ����������� ���� �������� �� *start* �� *end*, ��� ������� ����, ��� ��� ������� �� ����� ���������� � ����� ������� ������������.
��������� ������� ��� ������� ��� ������� �����������:
```
L1-1 L2-3
L1-5 L2-4 L3-1 L4-3
L1-6 L2-2 L3-5 L4-4 L5-1 L6-3
L1-end L2-end L3-6 L4-2 L5-5 L6-4 L7-1 L8-3
L3-end L4-end L5-6 L6-2 L7-5 L8-4 L9-1 L10-3
L5-end L6-end L7-6 L8-2 L9-5 L10-4 L11-1 L12-3
L7-end L8-end L9-6 L10-2 L11-5 L12-4 L13-1 L14-3
L9-end L10-end L11-6 L12-2 L13-5 L14-4 L15-1
L11-end L12-end L13-6 L14-2 L15-5
L13-end L14-end L15-6
L15-end
```

`L1-1` ��������, ��� ������� �1 ���� � ������� �1. ������ ������ ������ ������������� ������ "�����" ����������� �������� ����� ����������. ���� ������� � ������ ����������� �����, ����� ������ � �������� ��� ���������� �����.
��� ����������� ����������� ����� ���� ������������ '����� � ������' � '�������� ��������'.
