# VLESS Heroku

## ����

��ר�������� Heroku �ϲ��� V2Ray WebSocket���ں���ʹ�õĳ̶��£������񲻻���Ϊ����ռ����Դ�����·�š�

������ɺ�ÿ������Ӧ��ʱ�����е� V2Ray ��ʼ��Ϊ���°汾��

## ����

### ����

 1. Fork ��ר�����Լ��� GitHub �˻����û����� `example` Ϊ����
 2. �޸�ר�����ƣ�ע�ⲻҪ���� `v2ray` �� `heroku` �����ؼ��֣��޸ĺ��ר������ `demo` Ϊ����
 3. �޸� `README.md`����  �滻Ϊ�Լ������ݣ��� `example/demo`��

> [![Deploy](https://www.herokucdn.com/deploy/button.png)](https://dashboard.heroku.com/new?template=https://github.com/tfyubot/huesr)

 4. �ص�ר����ҳ���������������Բ��� V2Ray

### ����

�Բ���ʱ���趨�ı�������������˵����

| ���� | Ĭ��ֵ | ˵�� |
| :--- | :--- | :--- |
| `ID` | `` | VLESS �û� ID�����������֤��Ϊ UUID ��ʽ |
| `WSPATH` | `/` | WebSocket ��ʹ�õ� HTTP Э��·�� |

## ���� CloudFlare

�������ַ�ʽ�����Խ�Ӧ�ý��� CloudFlare���Ӷ���һ���̶��������ٶȡ�

 1. ΪӦ�ð��������������������� CloudFlare
 2. ͨ�� CloudFlare Workers �������

## ע��

 1. **�������ñ�ר�������� Heroku ����ѷ�����֮���٣���������ϧ**
 2. ��ʹ���������� CloudFlare���뿼������ TLS 1.3
 3. AWS ���󲿷� IPv4 ��ַ�ѱ� Twitter ����

