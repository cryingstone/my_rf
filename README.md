��˵����
0.ǰ��֪ʶ��������Ҫpython���������Բο���https://www.cnblogs.com/UncleYong/category/1188224.html
1.test_case�µ�����ֻ�Ǽ���ʾ����û���õ��������е����й���ģ�飬�����װ��db_operate.py��redis_operate.py�ȶ�û�õ���
2.���ݷ��룬���Է��뵽excel�У���Ҿ��Լ������Ż��ɣ�^_^


��������ʷ��
2019-04-03 v1.4 ���ӿɶ��Ե��Ż��ͱ���ģ��
2018-05-17 v1.3 �Ż�redis����
2018-04-25 v1.2 ����oracle���ݿ����
2018-04-24 v1.1 ������־������־������Ļ���ļ������־
2018-04-12 v1.0 ������


������ģ��˵����
python3.6 + requests + unittest + cx_oracle + HTMLTestRunner + os + sys + json + time + redis
1.Python3.6������������
2.requests��ģ���û�����httpЭ��get����post��������
3.unittest����֯���в�������
4.cx_oracle���������ݿ⣬ÿ������ǰ���������ݿ⣬����������ݣ���ʼ���������ݣ������mysql��һ����˼·��ģ����pymysql��
5.HTMLTestRunner������html��ʽ����ģ��
6.os����ȡ·��
7.sys�����û�������
8.json���Է��������ص��ַ���ת��Ϊ�ֵ䣬����������
9.time��ʱ��������ɵı��������ǣ�time_report.html
10.redis������redis���Ӷ�����֤�룬ģ���ȡ������֤��


�����Ŀ¼�ṹ���ܡ�
bin: ��ִ���ļ����������
conf: �����ļ�
core: �����ļ�
db_fix: ���ݿ����
log: ��־�ļ�
mockserver������������Ҫ�õ���mock����
reprot: ���Ա���
test_case: ���������������ļ�����# testSelect.py�ļ�������Ӧ��mock��Ŀ��mockserverĿ¼��
README.md: ˵���ļ�


������չ���ܡ�
����jenkins��jenkins��ִ�����
    windows�����£�����ű��ڣ�C:\test��ִ��python3 C:\test\bin\my_run.py %BUILD_NUMBER%
    linux�����£�����ű��ڣ�C:\test��ִ��python3 /opt/my_rf/bin/my_run.py $BUILD_NUMBER
	����ı�������Ϊ����6��2017-09-11_09_09_56_report.html����ǰ�������Ϊ�ڶ��ٴι���

