# BlinkEffectExample [![](https://jitpack.io/v/fitareq/BlinkEffectExample.svg)](https://jitpack.io/#fitareq/BlinkEffectExample)
# How to 
To get this project into your build:
### Step 1 
Add the JitPack repository to your build file
Add it in your root build.gradle at the end of repositories:

```
allprojects {
		repositories {
			...
			maven { url 'https://jitpack.io' }
		}
	}
  ```
### Step 2
Add the dependency

```
dependencies {
	        implementation 'com.github.fitareq:BlinkEffectExample:$latest_version'
	}
 ```
  
  ### Example
  
 ```
  Textview textView = findViewById(R.id.textview);

        BlinkEffect.blink(textView);
 ```
