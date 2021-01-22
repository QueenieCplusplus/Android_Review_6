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
             android:id="img"
             android:scaleType="centerCrop"
             android:srcCompat="@drawable/aaa"
           />
           
           <androidx.constraintlayout.widget.Guideline
              android:id="@+id/ggg"
              android:orientation=""
              app:layout_constaintGuide_end="@dimen/default_spacing"
           />
           
           <ImageButton
              android:id="imgB"
              android:scaleType="centerCrop"
              tools:src="@drawable/bbb"
           />
           
           </androidx.constraintlayout.widget.ConstraintLayout>
       
       </layout>
       
2. define dimens.

          // go to app/src/main/res/values/dimens.xml
          
          <?xml encoding="utf-8"?>
          
          <resources>
              <dimen name="default_spacing"> 16dp </dimen>
          </resources>
