autoDownloadDamll for Android

@author shoubo.wang@dmall.com
@date 2016-5-12
@version V1.0
@��������ڣ�installDmall.py

��������Ҫ�Ĺ���Ϊ�Զ���jenkins�����ز���װ���±����android apk�������л���Ϊpython 2.x�汾��
������Windows��Linux��Macϵͳ��

Ԥ��������
1��Android�ֻ��ڿ�����ѡ���п���������USB���ԣ�
2��Windowsϵͳ�Ͽ�����Ҫ��װ�ø��ֻ����������������ֻ���һ�㶼���Զ���װ����װһ�μ��ɣ���
3��python����������ʹ��2.7.x�İ汾��

���в���˵����
1��downloadURL = getDownloadURL(rootURL,"-dmtest")
�ú����ڶ�������λ��֧�������������ֱ�Ϊ"-dmtest"�����Ի���������-pre����Ԥ���������͡�-release��(��ʽ������

2��apkFile = isReadyForInstall(downloadURL)
�ú���Ҳ��֧�����������ģ��ڶ���������ָapp����Ŀ¼��Ĭ�ϣ�����д��Ϊ�ű����е�Ŀ¼����Ҳ֧��ָ��Ŀ¼����apkFile = isReadyForInstall(downloadURL, "D:\\Softwares\\")

3��need_uninstall = False
�ò���Ĭ��ΪFalse����Ϊ���ǰ�װ�����ְ�װ�ᱣ��֮ǰ�汾�����ݡ������¼����������Ҫ���ò�������ΪTrue��
a����Ҫȫ�°�װ
b���ֻ���װ�и��ߵİ汾��android��֧��ֱ�ӽ�����װ��
c����Ҫװ���⻷���İ������ڲ�ͬ�����İ�ǩ����һ�����������������Ҳֻ����ȫ�°�װ�����̣������ֻ�װ�в��Ի����İ�����������Ҫ��װ��ʽ�����İ���


����˵����
�˳���������Ŀǰjekins�Ĳ������ã��������jekins���Ĳ��ֲ������û���jekins���񲻿���ʱ���������п��ܻ�ֱ�ӳ�����֪Ϥ��