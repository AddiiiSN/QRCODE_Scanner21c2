# QRCODE_Scanner21c2


    <?xml version="1.0" encoding="utf-8"?>
    <RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingTop="@dimen/activity_vertical_margin">

    <Button
        android:id="@+id/button"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="QR CODE SCANNER"
        android:layout_alignParentBottom="true"/>

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical">

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nama :" />

        <TextView
            android:id="@+id/textviewNama"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Adi Setiawan"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Kelas" />

        <TextView
            android:id="@+id/textviewKelas"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="TI.21.C2"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Nim" />

        <TextView
            android:id="@+id/textViewNim"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="312110333"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        </LinearLayout>
    </RelativeLayout>
