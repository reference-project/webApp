ǰ�˿�ܻ�������
1. �����ش��뵽���أ�
����git clone https://github.com/zysusu/webApp.git
2. ��Ҫ���ذ�װ��node.js������ĿĿ¼�������޸�����vue2���£���node���������룺npm install ��װ������
3. ����ģʽ���ȴ���Ŀ���ҵ�vue2/configĿ¼����index.js����proxyTable�����������ע�͵�����ɣ�
proxyTable: {
           /* '/slsAdminApi': {
              target: 'http://exam.cuit.edu.cn:9999/WebApp/basic/web',    
    .........      
	        }*/
        },
Ȼ���vue2/src/config/settings.js,��hostֵ����Ϊ��Ӧ�ĺ�̨��Ŀ��ַ���磺http://192.168.169.182/WebApp/basic/web��
Ȼ����node���������룺npm run build
Build֮�󣬴�distĿ¼���ҵ�dist/static/img,�����������е�ͼƬ��Ȼ����dist/static/css���½�Ŀ¼static��Ȼ���static���½�Ŀ¼img��Ȼ�󽫸ոո��Ƶ�����ͼƬճ����dist/static/css/static/img��Ȼ��Ϳ���ѹ�����distĿ¼�����𵽷�����������

4. ���ؿ���ģʽ���޸Ĵ��룩���ȴ���Ŀ���ҵ�vue2/configĿ¼����index.js����proxyTable��targetֵ�޸�Ϊ��Ӧ�ĺ�̨��Ŀ��ַ���磺http://192.168.169.182/WebApp/basic/web��
Ȼ����node���������룺npm run dev
5. ע������������Ǻ���ϵ�����ɺ�̨�������ݣ�����Ҫ��������ѡ��ĺ�̨���Ŷ�����ֻ��һ����
6. ��ҳ���ֲ�ͼ��ʱ��д���ġ�Ϊimg01-img05
