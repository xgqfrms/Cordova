# this is a repo of my cordova test projects!  (for Android Apps)
## Windows10 x64 Pro + JDK v1.8.0_77 + nodejs v4.4.3 + cordova v6.1.1 + Android Studio v1.5.0.0  

# work directory :  

* G:\wwwRoot\Cordova\HTML5

### steps
>
* step1  
    install NodeJS  
	add the install path to System Environment path (options)  
	//H:\Program Files\nodejs  
* step2  
    CMD using npm  
	npm -g install cordova  
	add the install path to System Environment path (options)  
	//C:\Users\xray\AppData\Roaming\npm\node_modules\cordova\bin  
* step3  
    install JDK & JRE  
	add the install path to System Environment path (options)  
	//H:\Program Files\Java\jdk1.8.0_77\bin    
	//H:\Program Files\Java\jre1.8.0_77\bin  
* step4  
    install Android Studio & SDK  
	add the install path to System Environment path (options)  
	//H:\Android\AndroidStudio\bin  
	//H:\Android\sdk  
* step5  
    install Ant  
	add the install path to System Environment path (options)  
	//H:\Program Files\ant\apache-ant-1.9.7\bin  
>     



# test  create hello projects  

### steps  

> 
* step1    
    /*  
	CMD open project path  
	*/  
	cd G:/wwwRoot/Cordova/HTML5  
* step2  
    cordova create hello com.test.hello HelloWorld  
	/*  
	project name: hello  
	Android package path: com/test/hello  
	Main file: HelloWorld  
	*/  
* step3  
    cordova platform add android  
	/*  
	add the Android Runtime Environment  
	*/  
* step4  
    cordova bulid  
	/*  
	build the project  
	*/  
* step5  
    <1>Note: you need open Genymotion emulator   
	         or Android Studio emulator firstly  
    cordova run  
	/*  
	run the app  
	*/  
>  




###  description of hello project  

* config.xml 配置文件  
* hooks 自定义扩展功能目录  
* platforms 添加的运行时环境目录  
* pluins 引入的插件目录  
* www 开发目录  

***
***




