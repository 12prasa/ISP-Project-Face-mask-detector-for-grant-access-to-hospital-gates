# Project-Progress-Zoro-Steganography_information-Security-Project-IE3092

Mainfest.xml layout

<?xml version="1.0" encoding="utf-8"?>
<manifest
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:versionCode="4"
    android:versionName="1.0"
    package="com.meznik.Steganography">

    <uses-sdk
        android:minSdkVersion="14" />

    <application
        android:label="@ref/0x7f070000"
        android:icon="@ref/0x7f02000e"
        android:largeHeap="true">

        <activity
            android:theme="@ref/0x7f080016"
            android:name=".app.MainActivity"
            android:screenOrientation="1">

            <intent-filter>

                <action
                    android:name="android.intent.action.MAIN" />

                <category
                    android:name="android.intent.category.LAUNCHER" />
            </intent-filter>
        </activity>

        <activity
            android:theme="@ref/0x7f080017"
            android:label="@ref/0x7f070001"
            android:name=".app.EncodeActivity"
            android:screenOrientation="1" />

        <activity
            android:theme="@ref/0x7f080017"
            android:label="@ref/0x7f070003"
            android:name=".app.DecodeActivity"
            android:screenOrientation="1" />

        <activity
            android:theme="@ref/0x7f080018“a
            android:label="Help"
            android:name=".app.AboutActivity"
            android:screenOrientation="1" />

        <activity
            android:theme="@ref/0x7f080018"
            android:label="FAQ"
            android:name=".app.FaqActivity"
            android:screenOrientation="1" />
    </application>

    <uses-permission
        android:name="android.permission.WRITE_EXTERNAL_STORAGE" />

    <uses-permission
        android:name="android.permission.READ_EXTERNAL_STORAGE" />
</manifest>



Main layout

<?xml version="1.0" encoding="utf-8"?>
<LinearLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="1"
    android:layout_width="-1"
    android:layout_height="-1">

    <FrameLayout
        android:layout_width="-1"
        android:layout_height="dimension(257)"
        android:layout_weight="1090519040.000000">

        <ImageView
            android:gravity="0x11"
            android:id="@ref/0x7f0a0010"
            android:padding="dimension(2560)"
            android:layout_width="-1"
            android:layout_height="-1"
            android:scaleType="7"
            android:onClick="openImage" />

        <TextView
            android:textSize="dimension(5122)"
            android:textColor="@ref/0x7f050006"
            android:gravity="0x11"
            android:layout_gravity="0x51"
            android:id="@ref/0x7f0a0011"
            android:layout_width="-2"
            android:layout_height="-1"
            android:text="Tap here to load an image"
            android:textAllCaps="true"
            android:drawableStart="@ref/0x7f02000f" />
<View
        android:background="@ref/0x7f050004"
        android:layout_width="-1"
        android:layout_height="dimension(513)" />

    <EditText
        android:textColor="@ref/0x7f050004"
        android:gravity="0x11"
        android:id="@ref/0x7f0a0012"
        android:layout_width="-1"
        android:layout_height="-2"
        android:layout_marginLeft="dimension(2561)"
        android:layout_marginRight="dimension(2561)"
        android:hint="@ref/0x7f070004"
        android:maxLength="8"
        android:inputType="0x20081" />

    <LinearLayout
        android:layout_width="-1"
        android:layout_height="dimension(257)"
        android:layout_weight="1065353216.000000">

        <Button
            android:textColor="@ref/0x7f050001"
            android:id="@ref/0x7f0a0013"
            android:layout_width="dimension(257)"
            android:layout_height="-1"
            android:text="ENCODE"
            android:layout_weight="1065353216.000000"
            android:onClick="encodeButtonClicked"
            android:drawableStart="@ref/0x7f02000d" />

        <Button
            android:textColor="@ref/0x7f050001"
            android:id="@ref/0x7f0a0014"
            android:layout_width="dimension(257)"
            android:layout_height="-1"
            android:text="DECODE"
            android:layout_weight="1065353216.000000"
            android:onClick="decodeButtonClicked"
            android:drawableStart="@ref/0x7f02000c" />
    </LinearLayout>
</LinearLayout>
