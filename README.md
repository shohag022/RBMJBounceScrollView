# Bounce ScrollView
This document provides instructions for integrating the Stylish ScrollView Android SDK into your project.
# Getting Started
To get a Git project into your build:

> Step 1. Add the JitPack repository to your `build` file
``` build.gradle
allprojects {
		repositories {

			maven { url 'https://jitpack.io' }

		}
	}
```
> Step 2. Add the dependency to your `build.gradle`:
``` build.gradle
dependencies {
	        implementation 'com.github.shohag022:RBMJBounceScrollView:1.1'
	}
```
# Usage
> XML Code
``` build.gradle
    <com.rbmjltd.bouncescrollview.RBMJBounceScrollView
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        >
        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical"
            >


       // YOUR_CONTENT_HEAR


        </LinearLayout>

    </com.rbmjltd.bouncescrollview.RBMJBounceScrollView>
```
> Listener to the scrolling event of content of the `RBMJBounceScrollView`:
``` build.gradle
        RBMJScrollView.setOnScrollListener(new RBMJBounceScrollView.OnScrollListener() {
            @Override
            public void onScrolling(int scrollX, int scrollY) {


            }
        })
```
> Listener to the over-scrolling event of the `BounceScrollView`:
``` build.gradle
       RBMJScrollView.setOnOverScrollListener(new RBMJBounceScrollView.OnOverScrollListener() {
            @Override
            public void onOverScrolling(boolean fromStart, int overScrolledDistance) {

            }
        });
```

# Contact With Us
If you face any problem using this library then feel free to contact me.
To contact me message me on Facebook or email me at:

`Email`: shohag@rbmjltd.com

`Facebook`: <a href="https://www.facebook.com/M220719" rel="nofollow">Monir Hossain (Shohag)</a> 

# Authors
<a href="https://www.facebook.com/M220719" rel="nofollow">Shohag Hossain (Monir)</a>

