# Auxiliary Gadgets��Ŀ
## ��Ŀ���
������֮��С��Ϸʱ�򣬷����޷���̨�һ������ǲ����������Ŀ��

ʹ����PySide6/PyQT����Python��Ŀ��װ��һ��GUIС���ߣ�



## ��Ŀչʾ

###  <font color='bluesky' size=5> ���������</font>

- ʹ�÷ǳ��򵥣����� `ÿ��������`��Ȼ���¼��̵� `Ctrl + Shift + A` ���ɡ�

![image-20230616142254612](image/image-20230616142254612.png)

- ��������20��Ȼ����`Ctrl + Shift + A`��ע�⿴���Ͻǵ� ������ʾ��

![GIF 2023-6-16 14-24-41](image/GIF 2023-6-16 14-24-41.gif)

### <font color='bluesky' size=5>��̨�һ���</font>

- ʹ�÷ǳ��򵥣����� `����֮��`��Ȼ���� ���ش��ڼ��ɡ�

![image-20230616142309230](image/image-20230616142309230.png)

![GIF 2023-6-16 13-47-32](image/GIF 2023-6-16 13-47-32.gif)






## ��Ŀ��֯

��С���ߵ���Ŀ�ṹ������ʾ��

```bash
auxiliary-gadgets/
������ controllers/
��   ������ __init__.py
��   ������ controller_main.py
������ make/
��   ������ ����С����.spec
������ models/
��   ������ invoke_func/
��   ��   ������ __init__.py
��   ��   ������ mouse_click.py
��   ��   ������ window_operate.py
��   ������ __init__.py
��   ������ model_main.py
������ views/
��   ������ resources/
��   ��   ������ main.ui
��   ��   ������ trash.png
��   ��   ������ utils.qrc
��   ������ ui/
��   ��   ������ __init__.py
��   ��   ������ main_ui.py
��   ��   ������ utils_rc.py
��   ������ widgets/
��   ��   ������ __init__.py
��   ��   ������ view_main.py
��   ������ __init__.py
������ main.py
������ README.md
������ requirements.txt
```



## ��װ����

Pythonģ������
```bash
pip install -r requirements.txt
```


��Ҫ�Լ����´���Ļ���ʹ��make\����С����.spec ������
```bash
pyinstaller ����С����.spec
```



## ����
������빱�״���򱨸��������ʱ��GitHub���ύ��������⡣��ӭ���Ĺ��ף�