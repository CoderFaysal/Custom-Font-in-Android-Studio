### Add Custom Font in Android Studio Very Simple Way


#### To add fonts as resources, perform the following steps in the Android Studio:

- Right-click the res folder and go to New > Android resource directory. 
- In the Resource type list, select font, and then click OK.
- Add your font files in the font folder.


### If you Change the font in XML -

```
<TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:fontFamily="@font/lobster"
        />

```

### If you Change the font in Java -

```
Typeface typeface = getResources().getFont(R.font.myfont);
textView.setTypeface(typeface);

```



_@All Right Reserverd by Innovative Programmer ❤️_
