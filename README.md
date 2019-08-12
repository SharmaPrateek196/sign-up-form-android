<?xml version="1.0" encoding="utf-8"?>
<ScrollView xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    android:background="#ffffff"
    android:paddingBottom="15dp"
    xmlns:android="http://schemas.android.com/apk/res/android">
    xmlns:android="http://schemas.android.com/apk/res/android">

<RelativeLayout
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    >

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginRight="15dp"
                android:layout_marginLeft="15dp"
                android:padding="16dp"
                android:layout_marginTop="15dp"
                android:background="@drawable/rounded_corner">

                <ImageView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:src="@drawable/ic_person_orange_24dp" />

                <EditText
                    android:id="@+id/edFname"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#ffffff"
                    android:gravity=""
                    android:textStyle="bold"
                    android:hint="First Name"
                    android:inputType="textPersonName"
                    android:letterSpacing="0.1"
                    android:textColor="#fff"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp" />

                <EditText
                    android:id="@+id/edLname"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#00000000"
                    android:gravity=""
                    android:hint="Last Name"
                    android:textStyle="bold"
                    android:inputType="textPersonName"
                    android:letterSpacing="0.1"
                    android:textColor="#fff"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginRight="15dp"
                android:layout_marginLeft="15dp"
                android:layout_marginTop="10dp"
                android:padding="16dp"
                android:background="@drawable/rounded_corner">

                <ImageView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:src="@drawable/ic_email_black_24dp" />

                <EditText
                    android:id="@+id/mail"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#00000000"
                    android:textStyle="bold"
                    android:hint="Enter Your Email as User_ID"
                    android:inputType="text"
                    android:letterSpacing="0.1"
                    android:textColor="#000000"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="0.5dp"
                android:background="#5fff"
                android:layout_marginTop="10dp"></LinearLayout>


            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginRight="15dp"
                android:layout_marginLeft="15dp"
                android:padding="16dp"
                android:layout_marginTop="10dp"
                android:background="@drawable/rounded_corner">

                <ImageView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:src="@drawable/ic_password_orange_24dp" />

                <EditText
                    android:id="@+id/confirm_passwrd"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#00000000"
                    android:hint="Confirm Password"
                    android:inputType="textPassword"
                    android:letterSpacing="0.1"
                    android:textStyle="bold"
                    android:textColor="#fff"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginRight="15dp"
                android:layout_marginLeft="15dp"
                android:padding="16dp"
                android:layout_marginTop="10dp"
                android:background="@drawable/rounded_corner">

                <ImageView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:src="@drawable/ic_password_orange_24dp" />

                <EditText
                    android:id="@+id/passwrd"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#00000000"
                    android:hint="Password"
                    android:inputType="textPassword"
                    android:letterSpacing="0.1"
                    android:textColor="#fff"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp"
                    android:textStyle="bold" />
            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginRight="15dp"
                android:layout_marginTop="10dp"
                android:layout_marginLeft="15dp"
                android:padding="16dp"
                android:background="@drawable/rounded_corner">

                <ImageView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:src="@drawable/ic_phone_android_black_24dp" />

                <EditText
                    android:id="@+id/mobphone"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#00000000"
                    android:textStyle="bold"
                    android:hint="Mobile Number"
                    android:inputType="number"
                    android:letterSpacing="0.1"
                    android:textColor="#fff"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp" />
            </LinearLayout>


            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="horizontal"
                android:layout_marginRight="15dp"
                android:layout_marginLeft="15dp"
                android:layout_marginTop="10dp"
                android:padding="16dp"
                android:background="@drawable/rounded_corner">

                <ImageView
                    android:layout_width="20dp"
                    android:layout_height="20dp"
                    android:layout_gravity="center"
                    android:src="@drawable/ic_home_black_24dp" />

                <EditText
                    android:id="@+id/usraddr"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginLeft="15dp"
                    android:background="#00000000"
                    android:hint="Address"
                    android:inputType="text"
                    android:letterSpacing="0.1"
                    android:textColor="#fff"
                    android:textColorHint="#577C7171"
                    android:textSize="16dp"
                    android:textStyle="bold" />
            </LinearLayout>


            <Button
                android:id="@+id/sup"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginLeft="15dp"
                android:layout_marginRight="15dp"
                android:layout_weight="1"
                android:background="@drawable/rounded_corner_button"
                android:gravity="center"
                android:padding="15dp"
                android:text="SIGNUP"
                android:layout_marginTop="10dp"
                android:textColor="#000000"
                />

        </LinearLayout>
</RelativeLayout>
</ScrollView>
