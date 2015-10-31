# geetest_plug
##极验验证组件接口
设置captcha_id 


    void setCaptcha(captcha_id);
    
    
验证方法


    geeTest(custom_server_validate_url,plugGtListener)； 
    
    
custom_server_validate_url为服务器url

plugGtListener为验证回调接口  


    public interface PlugGtListener { 
         public void gtResult(String response){ 
             response为返回验证信息  
        } 
    } 
