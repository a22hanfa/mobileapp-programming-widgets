
# Rapport

I den här uppgiften har layouten ändrats samt tre olika widgets. De tre är EditText, ImageView och Button.

I appen används LinearLayout med en vertikal orientering, denna används som huvudlayout.
```
<LinearLayout android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:orientation="vertical"
    android:padding="16dp"
    xmlns:android="http://schemas.android.com/apk/res/android">

```

EditText-widgeten är placerad högst upp på appen sida. 
```
<EditText
        android:id="@+id/editText"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_marginBottom="16dp"
        android:paddingTop="15dp"
        android:paddingBottom="15dp"
        android:hint="Enter text here" />
```

Sedan kommer det en till LinearLayout som har en orientering horisontellt, i denna finns de två sista widgetsen ImageView och Button.
```
<LinearLayout
    android:layout_width="match_parent"
    android:layout_height="wrap_content"
    android:orientation="horizontal">

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_weight="1"
        android:layout_marginRight="8dp"
        android:src="@drawable/ic_launcher_background" />

    <Button
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="Click me" />

    
</LinearLayout>
```

Här är den slutliga produkten:
![](a22hanfa-Screenshot.png)

Läs gärna:

- Boulos, M.N.K., Warren, J., Gong, J. & Yue, P. (2010) Web GIS in practice VIII: HTML5 and the canvas element for interactive online mapping. International journal of health geographics 9, 14. Shin, Y. &
- Wunsche, B.C. (2013) A smartphone-based golf simulation exercise game for supporting arthritis patients. 2013 28th International Conference of Image and Vision Computing New Zealand (IVCNZ), IEEE, pp. 459–464.
- Wohlin, C., Runeson, P., Höst, M., Ohlsson, M.C., Regnell, B., Wesslén, A. (2012) Experimentation in Software Engineering, Berlin, Heidelberg: Springer Berlin Heidelberg.
