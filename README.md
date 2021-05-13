# pseudocode_Validate

1.	Get the Fat grams
2.      The amount of fat grams entered is greater than zero
3.	Get the calories
4.      ValidatemThe  amount of calories entered is greater than zero
5.	Calculate the percentage of calories from fat
6.	Display the percentage of calories from fat
7.      Validate The amount of calories entered is not greater  than nine times the amount of fat grams entered 
8.	If the percentage is less than 30 percent, display the food is low fat 
9.      Validate the Percentage of calories from fat

Module main ()
// Declare variables
  Declare Real Fat grams , calories, percentage of calories from fat

   
   // Get Fat grams
   Display "Enter the Fat grams." 
   Input Fat grams


   // Validate the Fat grams amount - Make sure it is not less than 0.
   While score < 0
      Display "ERROR: The score cannot be less than 0."
      Display "Enter the correct amount."
      Input amount
   End While


   // Get calories
  Display "Enter the calories." 
  Input calories


   // Validate the calories amount -Make sure it is not less than 0.
   While score < 0
      Display "ERROR: The score cannot be less than 0."
      Display "Enter the correct amount."
      Input amount
   End While

   // Calculate the percentage of calories from fat
   Percentage of calories from fat = (Fat grams × 9) ÷ calories

   // Display the percentage of calories from fat.
   Display "The percentage of calories from fat is", percentage of calories from fat

  // If the is less than 30 percent
  // display the food is low fat.
  If average > 30 Then
     Display " Display the food is low fat!"
  End If

// Get Percentage of calories from fat
Display "Enter  Percentage of calories from fat."
Input  Percentage of calories from fat


// Validate the Percentage of calories from fat
While score < 0 OR score > 9x fat_gram
  Display "ERROR: The score cannot be less than 0"
  Display "or greater than 9x fat_gram."
  Display "Enter the correct amount."
  Input amount
End While
