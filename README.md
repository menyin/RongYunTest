#��ʢ��ʹͨѶϵͳCSIM

##ʹ�ò���
###1.���뾲̬��Դ
css/CSIM_All.css
js/CSIM_All.js

###2.��дhtmlģ��
<div ng-controller="main" class="CSIM_UI">
    <h2>��ǰ�û���<span ng-bind="user"></span></h2><br/>
    <label>Ŀ���û�Id��</label><input class="input" ng-model="targetId">
    <button class="btn" ng-click="setconversation()"></button><br/> <br/><!--������Ϣ-->
    <label>Ŀ��ͷ�Id��</label><input class="input" ng-model="customerserviceId">
    <button class="btn" ng-click="setcustomerservice()"></button><br/> <br/><!--������ѯ-->
    <rong-widget></rong-widget>
</div>

###3.���õ�ǰ�û�appkey��token
<script>
    /*��ʼ������*/
    angular.module('CSIM_Config', ['RongWebIMWidget'])
    .factory('setting', ['WebIMWidget', function () {
        return {
            appkey: '3argexb6r934e',//���д��appkey
            token: "b/jvjEFD41TIVT0nsf9+L3ryPPkHsvRwWZV8SVI5ICcZ2I5Nl4OdNO01OjZxjjmVlD2dmk4RZ90="//���д��token
        }
    }]);
</script>

###ע�⣺�뱣��css��images��̬��Դ�ļ��е����·������

##��ʾ
 ͬʱ��user1.html��user2.html�����ɽ���ͨ����ʾ

