Redmine ������
1.	�鿴��˾redmine���ݿ�ṹ������ز����޸ĳ��빫˾һ��
2.	��redmine_statistics�ļ��п�������˾redmine��vendor/pluginsĿ¼��
3.	��Ҫ��װ�Ĳ���У�gchartrb, ��װ����:gem install gchartrb
4.	��redmine��Ŀ¼���������� rake db:migrate_plugins RAILS_EVN=production �޸����ݿ⣬����ǰ�ȱ������ݿ�
5.	��database.rake�ļ�������lib/tasksĿ¼�£�������
6.	ʹ������/sbin/service crond start ������ʱ����(/sbin/service crond stop ֹͣ)
7.	�༭�ļ�crontab ,����rake����ʹ������ 0 1 * * * root cd redmineĿ¼/  && rake RAILS_ENV=production statistics:daily_task --trace
8.	����������
