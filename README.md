 dataBinding {
        enabled true
    }
    
    <layout xmlns:android="http://schemas.android.com/apk/res/android" xmlns:tools="http://schemas.android.com/tools"
        xmlns:app="http://schemas.android.com/apk/res-auto">
    <data>
        <variable name="main" type="com.devmina.droid_ant.colorit.MainActivity"/>

    </data>
    </layout>
    
        val binding : ActivityMainBinding =
            DataBindingUtil.setContentView(this, R.layout.activity_main)
