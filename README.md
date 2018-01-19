//*  # Lost-In-Java-World
Working hard on learning Java and Android Studio. I have been following the same lesson plan and I have redone the plan at least 20 times now and haven't got it right yet. Working on this current Errors  now but I don't know which option I should try. Any suggestions?*/



 @Override
        protected void onCreate(Bundle savedInstanceState) {        
            super.onCreate(savedInstanceState);                    
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







