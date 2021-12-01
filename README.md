# LibraryTest

Step1:
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  
  Step2:
  	dependencies {
	        implementation 'com.github.begumkocahuyuk:LibraryTest:Tag'
	}
