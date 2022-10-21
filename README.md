# Tugas-Pert.4-Pemrograman-Mobile1-

<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:layout_width="match_parent"
    android:layout_height="match_parent"

    android:paddingBottom="@dimen/activity_vertical_margin"
    android:paddingTop="@dimen/activity_vertical_margin"
    android:paddingRight="@dimen/activity_horinzontal_margin"
    android:paddingLeft="@dimen/activity_horinzontal_margin">

    <Button
        android:id="@+id/buttonScan"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:text="Scan QR Code"

        android:layout_alignParentBottom="true" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="vertical"
        android:layout_centerVertical="true">

        <TextView
            android:id="@+id/textView"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Nama" />

        <TextView
            android:id="@+id/textViewNama"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="Risky Parmonanangan Siringoringo"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="Kelas" />

        <TextView
            android:id="@+id/textViewKelas"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="TI.21.C2"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

        <TextView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="NIM" />

        <TextView
            android:id="@+id/textViewNIM"
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:text="312110244"
            android:textAppearance="@style/TextAppearance.AppCompat.Large" />

    </LinearLayout>

</RelativeLayout>
