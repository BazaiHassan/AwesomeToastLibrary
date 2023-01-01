# AwesomeToastLibrary

 Step 1. Add the JitPack repository to your build file 
 Add it in your root build.gradle at the end of repositories:
 
	 allprojects {
			repositories {
				...
				maven { url 'https://jitpack.io' }
			}
		}
  
  

Step 2. Add the dependency

	dependencies {
	        implementation 'com.github.BazaiHassan:AwesomeToastLibrary:1.1'
	}
	
## Here some examples:

	            AwesomeToast.popSuccess(this, "This is a success toast",AwesomeToast.LENGTH_LONG).show()
<img align="center" src="https://github.com/BazaiHassan/images/blob/main/awesometoast/1672537817512.jpg"/>
  
  	            AwesomeToast.popInfo(this, "This is an info toast",AwesomeToast.LENGTH_LONG).show()
<img align="center" src="https://github.com/BazaiHassan/images/blob/main/awesometoast/1672537817495.jpg"/>

	            AwesomeToast.popError(this, "This is an error toast",AwesomeToast.LENGTH_LONG).show()
<img align="center" src="https://github.com/BazaiHassan/images/blob/main/awesometoast/1672537817485.jpg"/>

	            AwesomeToast.popWarning(this, "This is a warning toast",AwesomeToast.LENGTH_LONG).show()
<img align="center" src="https://github.com/BazaiHassan/images/blob/main/awesometoast/1672537817504.jpg"/>



