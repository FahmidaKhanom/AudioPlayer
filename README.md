<LinearLayout xmlns:android="http://schemas.android.com/apk/res-autotp://"


    orientation="vertical"
    android:layout_height="match_parent"
    android:layout_width="match_parent"
    android:orientation="vertical">

    <androidx.recyclerview.widget.RecyclerView
        android:id="@+id/recyclerView"
        android:layout_height="match_parent"
        android:layout_weight="1"
        android:layout_width="match_parent" />

    <SeekBar

        style="@style/Widget.AppCompat.SeekBar.Discrete"
        android:id="@+id/seekBar"
        android:layout_height="wrap_content"
        android:layout_weight="0"
        android:layout_width="match_parent" />

</LinearLayout>
