# Lost-In-Java-World
Working hard on learning Java and Android Studio. I have been following the same lesson plan and I have redone the plan at least 20 times now and haven't got it right yet. Working on this current Errors  now but I don't know which option I should try. Any suggestions?
 @Override
        protected void onCreate(Bundle savedInstanceState) {        //  "(savedInstanceState)// "The error is here I don't unders 
            super.onCreate(savedInstanceState);                     //   (savedInstanceState);//
            setContentView(R.layout.activity_display_message);


package com.bigdaddytheprocaddy.myfirstapp2;

import android.content.Intent;
import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
    
                                                                    Create local variable 'savedInstanceState'
                                                                    Create field 'savedInstanceState'
                                                                    Create parameter 'savedInstanceState'
                                                                    Rename reference
                                                                    "Which one of these do I choose to correctly fix the error and                                                                            why...telling me where I should be reading in the Android training                                                                      would be great, I want to know why. Thanks"
    
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);
    }

    /**
     * Called when the user taps the Send button
     */
    public void sendMessage(View view) {
        // Do something in response to button
        //An error remains for DisplayMessageActivity, but that's okay; you'll fix that in the next section.

        Intent intent = new Intent(this, DisplayMessageActivity.class);

        @Override
        protected void onCreate(Bundle savedInstanceState) {
            super.onCreate(savedInstanceState);
            setContentView(R.layout.activity_display_message);

            // Get the Intent that started this activity and extract the string
            intent = getIntent();
            String message = intent.getStringExtra(ExtraData);

            // Capture the layout's TextView and set the string as its text
            TextView textView = findViewById(R.id.textView);
            textView.setText(message);
    }
Information:Gradle tasks [:app:assembleDebug]
C:\Users\bigda\AndroidStudioProjects\MyFirstApp2\app\src\main\java\com\bigdaddytheprocaddy\myfirstapp2\MainActivity.java
Error:(27, 32) error: ';' expected
Error:(27, 58) error: ';' expected
Error:(39, 2) error: reached end of file while parsing
Error:Execution failed for task ':app:compileDebugJavaWithJavac'.
> Compilation failed; see the compiler error output for details.
Information:BUILD FAILED in 5s
Information:4 errors
Information:0 warnings
Information:See complete output in console






