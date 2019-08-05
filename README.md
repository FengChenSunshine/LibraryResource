# LibraryResource
一个提供了项目中基础资源的库！[![](https://jitpack.io/v/FengChenSunshine/LibraryResource.svg)](https://jitpack.io/#FengChenSunshine/LibraryResource)
[![](https://img.shields.io/badge/license-MIT-brightgreen.svg)](https://github.com/FengChenSunshine/LibraryModel/blob/master/LICENSE)

这个库里包含项目中使用到的一些、颜色、动画、style、theme等基础资源！！！

## 1.使用
How to
Step 1. Add the JitPack repository to your build file,Add it in your root build.gradle at the end of repositories:

    allprojects {
		    repositories {
			      ...
			      maven { url 'https://jitpack.io' }
		    }
	  }

Step 2. Add the dependency

    dependencies {
	          implementation 'com.github.FengChenSunshine:LibraryResource:v1.0.0'
	  }
## 2.版本说明
 
### 1.0.1
   1.修改精简Dialog主题,并在Theme中配置Dialog默认主题;
   
   2.提供3种Dialog主题：
   
   ①继承自@android:style/Theme.Dialog，不建议使用；
   
   ②继承自Theme.AppCompat.Light.Dialog；
   
   ③继承自AppTheme.NoActionBar。
