/**
 * ���� : ʹ js ����ʵ�� include ����
 *      ʾ�� <script src="tool.js" include="head.html"></script>
 *      src ��λ���ýű�, include ����Ըýű���.html�ļ�
 * ע�� :
 *      ���ű�����UI����ʹ��
 *      Ϊ�˷�������������, ��Ҫʹ����js��
 *      chrome ��������ص���ʱ����� --allow-file-access-from-files ��������
 *      firfox ���������"about:config" �� security.fileuri.strict_origin_policy ��Ϊ false
 * ���� : Edgar.lee
 */
<script __del>
/**
 * ���� : ���ؿɵ��� of ����е�js��չ
 * ע�� : ��Ҫ���� htmlLoad �ļ����ļ���
 * ���� : Edgar.lee
 */
+function () {
    //��ǰ�ļ�, htmlLoad �Զ���䲻Ҫ�޸�
    var src = "";

    //����ϵͳ��Ŀ¼
    window.ROOT_URL = src + "../..";
    //���ÿ�ܸ�Ŀ¼
    window.OF_URL   = ROOT_URL + "/include/of";
    //������ͼ��Ŀ¼
    window.VIEW_URL = ROOT_URL + "/view";

    //����jquery
    document.write('<script src' + '="' + OF_URL + '/att/link/jquery.js"></' + 'script>');
    //����L.js addin��������ĿΪ��Ŀ¼��ָ��js���ɲ��λ��
    document.write('<script src' + '="' + OF_URL + '/att/link/L.js" addin=""></' + 'script>');
}();
</script>