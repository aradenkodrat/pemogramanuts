lAYOUT LOADING SCREEN


    <TextView
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <ImageView
        android:id="@+id/imageView"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        app:srcCompat="@drawable/pm"
        tools:layout_editor_absoluteX="0dp"
        tools:layout_editor_absoluteY="0dp" />

</androidx.constraintlayout.widget.ConstraintLayout>
<img width="455" alt="WhatsApp Image 2023-06-02 at 15 56 37" src="https://github.com/aradenkodrat/pemogramanuts/assets/101814131/ce848fd8-dd8f-4054-8875-2c48fb7a8245">

LAYOUT LOGIN
<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
     android:background="@color/purple_700"
    tools:context=".MainActivity">

    <TextView
        android:id="@+id/tvlogin"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:text="LOGIN"
        android:layout_marginTop="150dp"
        android:layout_centerHorizontal="true"
        android:textColor="@color/white"
        android:textSize="28sp"
        android:textStyle="bold"
        app:layout_constraintBottom_toBottomOf="parent"
        app:layout_constraintEnd_toEndOf="parent"
        app:layout_constraintStart_toStartOf="parent"
        app:layout_constraintTop_toTopOf="parent" />

    <EditText
        android:id="@+id/username"
        android:layout_width="match_parent"
        android:layout_height="wrap_content_countent"
        android:layout_below="@id/tvlogin"
        android:layout_margin="20dp"
        android:layout_marginStart="20dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="20dp"
        android:layout_marginBottom="20dp"
        android:background="#38ffffff"
        android:hint="username"
        android:drawableStart="@drawable/ic_baseline_person_2"
        android:textColorHint="@color/white"
        android:padding="20dp"/>
    <EditText
        android:id="@+id/password"
        android:layout_width="match_parent"
        android:layout_height="wrap_content_countent"
        android:layout_below="@id/tvlogin"
        android:layout_margin="20dp"
        android:layout_marginStart="20dp"
        android:layout_marginTop="20dp"
        android:layout_marginEnd="20dp"
        android:layout_marginBottom="20dp"
        android:background="#38ffffff"
        android:hint="password"
        android:drawableStart="@drawable/ic_baseline_person_2"
        android:textColorHint="@color/white"
        android:padding="20dp"/>
    <Button
        android:id="@+id/tvlogin"
        android:layout_width="wrap_content"
        android:layout_height="wrap_content"
        android:layout_below="@+id/password"
        android:layout_centerHorizontal="true"
        android:backgroundTint="@color/cardview_dark_background"
        android:text="LOGIN" />


<img width="202" alt="WhatsApp Image 2023-06-02 at 16 16 40" src="https://github.com/aradenkodrat/pemogramanuts/assets/101814131/9c4f9cac-6143-47d4-aa42-8661fa36d85a">

