# EdiTextStyle

|<img src="https://github.com/gzeinnumer/EdiTextStyle/blob/master/preview/example1.jpg" width="200"/>|<img src="https://github.com/gzeinnumer/EdiTextStyle/blob/master/preview/example2.jpg" width="200"/>|
|--|--|

- background_filled_yellow_radius.xml
```exml
<?xml version="1.0" encoding="utf-8"?>
<shape xmlns:android="http://schemas.android.com/apk/res/android"
    android:shape="rectangle">
    <solid android:color="#FEFFDE" />
    <corners android:radius="@dimen/radius" />
</shape>
```

- activity_main.xml
```xml
<LinearLayout
    android:layout_width="match_parent"
    android:layout_height="48dp"
    android:layout_marginTop="@dimen/def_margin"
    android:background="@drawable/background_filled_yellow_radius"
    android:gravity="center">

    <AutoCompleteTextView
        android:id="@+id/et_username"
        android:layout_width="0dp"
        android:layout_height="wrap_content"
        android:layout_margin="@dimen/def_margin_half"
        android:layout_weight="1"
        android:background="@drawable/background_filled_yellow_radius"
        android:drawableStart="@drawable/ic_person_e"
        android:drawableLeft="@drawable/ic_person_e"
        android:drawablePadding="@dimen/def_margin_half"
        android:hint="Username"
        android:singleLine="true"
        android:textColorHint="@color/colorPrimary" />
</LinearLayout>
```

---

```
Copyright 2021 M. Fadli Zein
```