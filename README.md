spring cloud demo ,ʵ�����������ο� http://blog.didispace.com/springcloud1/

server-cluster-1 : ����ע������ �����̿��Դ��jar�����������ʵ���γ�һ��ע�����Ⱥ��������������3��ʵ����������ʽ���£�
                   java -jar server-cluster-1.jar --spring.profiles.active=peer1
                   java -jar server-cluster-1.jar --spring.profiles.active=peer2
                   java -jar server-cluster-1.jar --spring.profiles.active=peer3
service-A :����ע�� ע��������ʵ�������Բο�server-cluster-1
gateway:   �������� 
eureka-feign: ������,ʹ�õ���feign,Ҳ����ʹ��ribbon,feign,���ܸ�ǿ��Ĭ��֧�ַ�����õĸ��ؾ��⣬�Լ��۶Ϻͽ��� 