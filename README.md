# CALCULATOR-Code
Android studio
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity"
    android:padding="20dp"
    android:orientation="vertical"
    android:background="@color/pastel">

    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="CALCULATOR"
        android:textSize="25sp"
        android:layout_marginBottom="16dp"
        android:textColor="@android:color/black" />

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_marginBottom="20dp">

        <EditText
            android:id="@+id/first_no"
            android:layout_width="102dp"
            android:layout_height="59dp"
            android:ems="10"
            android:layout_marginHorizontal="50dp"
            android:hint="Enter" />

        <EditText
            android:id="@+id/second_no"
            android:layout_width="102dp"
            android:layout_height="59dp"
            android:ems="10"
            android:hint="Enter" />

    </LinearLayout>

    <LinearLayout
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:orientation="horizontal"
        android:layout_marginBottom="20dp">

        <TextView
            android:textSize="35sp"
            android:id="@+id/answer"
            android:layout_width="102dp"
            android:layout_height="59dp"
            android:layout_marginHorizontal="50dp"
            android:hint="ans" />

    </LinearLayout>

    <LinearLayout
        android:orientation="vertical"
        android:layout_marginLeft="250dp"
        android:layout_width="wrap_content"
android:layout_height="wrap_content"
        android:layout_marginBottom="30dp">

        <Button
            android:id="@+id/sub"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="-"
            android:textSize="25sp"
            android:layout_marginBottom="16dp" />

        <Button
            android:id="@+id/add"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="16dp"
            android:text="+"
            android:textSize="25sp"
            tools:ignore="OnClick" />

        <Button
            android:id="@+id/div"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:text="/"
            android:textSize="25sp"
            android:layout_marginBottom="16dp" />

        <Button
            android:id="@+id/mul"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="16dp"
            android:text="X"
            android:textSize="25sp"/>

        <Button
            android:id="@+id/equals"
            android:layout_width="wrap_content"
            android:layout_height="wrap_content"
            android:layout_marginBottom="16dp"
            android:text="="
            android:textSize="35sp"/>
    </LinearLayout>


</LinearLayout>
