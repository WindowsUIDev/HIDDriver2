������������������ʹ����������ִ�������̲�����


һ����Ŀ���룺
����ʹ��Visual Studio 2019��


����������װ��
1���ر�ǩ��У�飬��������ģʽ��
bcdedit /set nointegritychecks on
bcdedit /set testsigning on

2��ʹ��devcon��װ����������ȹر�360��ɱ�������
cd G:\workspace_github\loki-hidriver\x64\Debug\KMDFDriver
& "D:/Windows Kits/10/Tools/x64/devcon.exe" find "root\hidriver"
& "D:/Windows Kits/10/Tools/x64/devcon.exe" remove "root\hidriver"
& "D:/Windows Kits/10/Tools/x64/devcon.exe" install hidriver.inf "root\hidriver"

3����װ��������־�ļ���������������������װ����ϸ��־��
%windir%\\inf\\setupapi.dev.log
C:\Windows\INF\setupapi.dev.log


������Ŀ��Դ��
Ŀǰֻ�����win10��Щ�����Ե��������������Դ��loki-hidriver��Ŀ����лԭ������hedgar2017��
https://github.com/hedgar2017/loki-hidriver