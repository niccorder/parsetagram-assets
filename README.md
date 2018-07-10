# Assets for Parsetagram
These are the assets for parsetagram that I used in my application. I'd reccommend you copy them over carefully because you will, and can break your application if you don't do it correctly.

Make sure to commit prior to doing this!!!! If anything breaks, you can tackle it then.

You will need to enable vector drawables in your application, to do this you will have to add the following to your app/build.gradle.
```
 android {
   defaultConfig {
       // Add this line below into the default config
       vectorDrawables.useSupportLibrary = true
    }
 }
 ```

 One other thing to note!!!!
 Whenever you use images in your application on an imageview you must now use `app:srcCompat` instead of `android:src`.


