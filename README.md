or create a new repository on the command line
echo "# graduate" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/MaloneRe/graduate.git
git push -u origin master
or push an existing repository from the command line
git remote add origin https://github.com/MaloneRe/graduate.git
git push -u origin master


1�����Ƚ�����Ŀ�ļ��У�ͨ������ git init �����Ŀ¼���git���Թ����Ĳֿ�

git init
2�����ļ����ӵ��汾���У�ʹ������ git add .���ӵ��ݴ�������ȥ����Ҫ���Ǻ����С���㡰.������Ϊ�����ļ����µ������ļ�

git add .
3�������� git commit����Git�����ļ��ύ���ֿ⡣������Ϊ�ύ˵��

git commit -m 'first commit'
4��������Զ�̿�

git remote add origin ���Զ�̿��ַ
�磺

git remote add origin https://github.com/cade8800/ionic-demo.git
5����ȡԶ�̿��뱾��ͬ���ϲ������Զ�̿ⲻΪ�ձ�������һ�������������ύ��ʧ�ܣ�

git pull --rebase origin master
6���ѱ��ؿ���������͵�Զ�̣�ʹ�� git push���ʵ�����ǰѵ�ǰ��֧master���͵�Զ�̡�ִ�д�������Ҫ�������û��������룬��֤ͨ���󼴿�ʼ�ϴ���

git push -u origin master
*��״̬��ѯ����

git status