# DubboInvoker
 a develop tool help test dubbo service.<br/>
      call dubbo service with several click.<br/>
      auto generate param value according param type.<br/>
      support user define param value in doc comment.<br/>
      <br/><br/>

       usage:
       step1: right click on dubbo service method 
       step2: click DubboInvoker 
       step3: check auto generate param value 
       step4: click invoke button

       
       user define param value example:
       
    /**
     *
     * @param a id
     *          example=asdfasdf
     * @param b 商户号
     *          example=123
     * @param exportParam realParam
     *                    example={"billDate":20190101}
     */
    void getData(String a, int b, ExportParam exportParam);
       

       
       1. new line for example
       2. start with token "example="