package com.example.nilamadhab.score;

import android.support.v7.app.AppCompatActivity;
import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.Switch;
import android.widget.TextView;
import android.widget.Toast;

import org.w3c.dom.Text;

public class MainActivity extends AppCompatActivity {

    Button button1 ;
    Button button2 ;
    Button button3 ;
    Button button4 ;
    Button button5 ;
    Button button6 ;

    Button buttonwd ;
    Button buttonnb ;

    Button buttonwk ;

    Button buttonreset;

    TextView textView_run;
    TextView textView_wk;
    TextView textview_ball;






    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        button1 = (Button) findViewById(R.id.button_1);
        button2 = (Button) findViewById(R.id.button_2);
        button3 = (Button) findViewById(R.id.button_3);
        button4 = (Button) findViewById(R.id.button_4);
        button5 = (Button) findViewById(R.id.button_5);
        button6 = (Button) findViewById(R.id.button_6);

        buttonwd = (Button) findViewById(R.id.button_wd);
        buttonnb = (Button) findViewById(R.id.button_nb);

        buttonwk = (Button) findViewById(R.id.button_wk);

        buttonreset = (Button) findViewById(R.id.button_reset);

        textView_run = (TextView) findViewById(R.id.textview_run);
        textView_wk = (TextView) findViewById(R.id.textview_wicket);
        textview_ball=(TextView) findViewById(R.id.textView_ball);


    }

    public void onclick(View v)
    {
        int run ;
        int result ;
        switch (v.getId())
        {
            case R.id.button_1:

                if(textView_run.getText()=="0") {
                    textView_run.setText("1");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);
                }

                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }



                break;
            case R.id.button_2:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("2");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+2;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }

                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }



                break;
            case R.id.button_3:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("3");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+3;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }

                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }


                break;

                case R.id.button_4:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("4");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+4;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }

                // For Calculating the NO of BALLS
                    if(textview_ball.getText()=="0")
                    {
                        textview_ball.setText("1");
                    }
                    else
                    {
                        String num4 = textview_ball.getText().toString();

                        Integer num1=Integer.parseInt(num4);

                        int num2=num1+1;

                        String num3 = String.valueOf(num2);

                        textview_ball.setText(num3);

                    }


                break;
            case R.id.button_5:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("5");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+5;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }
                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }


                break;
            case R.id.button_6:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("6");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+6;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }
                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }


                break;
            case R.id.button_wd:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("1");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    Integer num1=Integer.parseInt(num);

                    Integer num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }

                Toast.makeText(getApplicationContext(),"Wide Ball",Toast.LENGTH_SHORT).show();
                break;
            case R.id.button_nb:

                if(textView_run.getText()=="0")
                {
                    textView_run.setText("1");
                }
                else
                {
                    String num = textView_run.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textView_run.setText(num3);

                }


                Toast.makeText(getApplicationContext(),"No Ball.. WoW It's a FREE HIT",Toast.LENGTH_SHORT).show();
                break;
            case R.id.button_wk:

                if(textView_wk.getText()=="0")
                {
                    textView_wk.setText("1");
                }
                else
                {
                    String num = textView_wk.getText().toString();

                    int num1=Integer.parseInt(num);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textView_wk.setText(num3);

                }

                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }

                Toast.makeText(getApplicationContext(),"Wicket",Toast.LENGTH_SHORT).show();
                break;

            case R.id.button_total:

                String num = textView_run.getText().toString();

                String wk = textView_wk.getText().toString();

                Toast.makeText(getApplicationContext(),"Total Run : "+ num + "Total Wicket : "+ wk ,Toast.LENGTH_LONG).show();
                break;

            case R.id.button_reset:

                if(textview_ball.getText()=="0")
                {
                    textview_ball.setText("1");
                }
                else
                {
                    String num4 = textview_ball.getText().toString();

                    int num1=Integer.parseInt(num4);

                    int num2=num1+1;

                    String num3 = String.valueOf(num2);

                    textview_ball.setText(num3);

                }

                break;
        }

    }





}
