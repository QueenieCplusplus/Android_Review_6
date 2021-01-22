# Android_Review_6
Logcat &amp; Lifecycle

1. design layout with UI element. And add on Guideline to make a space between ImageView & ImageButton.

       //activity_main.xml
       
       <?xml encoding="utf-8"?>
       
       <layout>
       
           <data>
           </data>
           
           <androidx.constraintlayout.widget.ConstraintLayout
              tools:context=".MainActivity"
           >
           
           <ImageView
             android:id=""
             android:scaleType="centerCrop"
             android:srcCompat="@drawable/aaa"
           />
           
           
           
           <ImageButton
              android:id=""
              android:scaleType="centerCrop"
              tools:src="@drawable/bbb"
           />
           
           </androidx.constraintlayout.widget.ConstraintLayout>
       
       </layout>
       
       
