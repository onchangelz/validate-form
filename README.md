#validate-form.js
##validate-form.js��ʲô?
һ������jQuery/zepto.js��ǿ��ı���֤���������������еĻ�������֤���ܣ����ҹ��ܿ���չ��

##validate-form.js����Щ���ܣ�

* ����ʹ�õ�`������֤`����
    *  �ǿ���֤�������ʽ��֤���ֻ������ʽ��֤��������֤�����ֺ���ĸ����ϡ�������֤
    *  ������֤���й����ո�ʽ��֤
* ֧��`�첽������֤`����
* ֧�ֿ���չ��`���⹦����֤`����

##��֤����

```javascript
var validateParams = {
    //�ص���������ǰ����֤ͨ���Լ���ͨ���������
    onChange: function (isValid, $elem, msg) {
        /*
        isValid:��ǰ��֤�Ƿ�ͨ����true��ͨ����false����ͨ����
        $elem:��ǰ����֤�ı�Ԫ�أ�jQuery����
        msg����֤δͨ��ʱ�Ĵ�����ʾ
        */
        //��������֤ͨ���Լ�δͨ��ʱ��dom����
        if (isValid) {
            $elem.next().removeClass("error");
        } else {
            $elem.focus().next().text(msg).addClass("error");
        }
    }
};
```
##��������

```javascript
  var ihubo = {
    nickName  : "felixpan",
    github : "https://github.com/pmg1989"
  }
```

##���ⷴ��
��ʹ�������κ����⣬��ӭ�������ң�������������ϵ��ʽ���ҽ���

* �ʼ�(972401854@qq.com, ����#����@��)
* QQ: 972401854