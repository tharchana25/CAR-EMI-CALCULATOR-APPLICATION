# CAR-EMI-CALCULATOR-APPLICARTION
The purpose of this project is to create an android moblie application where the user can calculate their equated monthly installment(EMI) based on the mortgage amount tenure and the interest rate.

The formula to calculate EMI is 
                                    E = P * (r(1+r)n)/((1+r)n-1) 
where 
E = The EMI payable on the car loan amount.
P = The Car loan Principal Amount.
r = The interest rate value computed on a monthly basis.
n = The loan tenure in the form of months.
The down payment amount has to be deducted from the principal amount paid towards buying the Car.

Develop an application that makes use of this AIDL service to calculate the EMI. 
  This application should have 
  -Four  EditText to read PRINCIPAL AMOUNT,DOWN PAYMENT,INTEREST RATE, LOAN TERM(in months).
  -Button named as “Calculator Monthly EMI”.
  -On click of Button, the result should be shown in a TextView.
  Also,calculate the EMI by varying the Loan term and Interest Rate value.

STEPS FOR IMPEMENTATION:
1.	Open Android Studio->click on File-new->click on new project->select empty activity ->name My Application as CarEmiCalculatorApplication ->select language as java .
2.	Designing the UI with activity_main.xml
  1.Drag and drop the following components by palette
  2.Total eight Plain text (EditText) -Five plain text is used for calculation part:-   1-principal amount.
                                                                                        2-Down payment.
                                                                                        3-interest rate.
  	                                                                                    4-loan term(in months).
                                                                                        5-insurance(in years).
                                                                                        6.other three plain text is used for result(car emi,insurance amount,total amount),they are recognized by their id and
                                                                                          set constraints.
  3.One Button name it as “Calculator Monthly EMI”and assign its id as monthlyemi and set constraints.
  4.Total eight TextView:-1-Five TextView is used for calculation part(principal amount,down payment,interest rate,loan term(in months),insurance(in years) and
  	                      2-other three TextView is used for calculation of result(car emi,insurance amount,total amount),they are recognized by their text attribute and set constraints.
  5.Image-copy image from any sources and go to android-> app->res->drawable->left click on drawable ->click on paste,then the image pasted then  by using ImageView  palette,drag the image in to screen window and   set constraints.
3.Design the MainActivtiy.java
4.Write java code for implementation of CAR EMI CALCULATOR Application.





