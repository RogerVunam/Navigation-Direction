# Navigation-Direction


# Step 0 : Set up library


# Step 1 : Trong activity_main.xml
```
 <fragment
            android:id="@+id/fmNavHostGraph"
            android:name="androidx.navigation.fragment.NavHostFragment"
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            app:defaultNavHost="true"
            app:navGraph="@navigation/nav_graph" />
```
            
            
# Step 2 : Set up Navigation


# Step3 : SplashScreenFM

```
private fun changeScreen() {
        var handler: Handler = Handler(Looper.myLooper()!!)
        handler.postDelayed(Runnable {
            findNavController().navigate(R.id.action_splashScreenFM_to_signInFM)
        }, 3000)
    }
    
```



# Step 4 :
 
