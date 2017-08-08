# SimpleBasic-Sec-20-2
Below is the code I created in an attempt to meet the parameters of the assignment but I cannot get the program to output individual branch closed messages. Please advise: 

TextWindow.Title="Branch Availability"
TextWindow.WriteLine("Branches have the following availability.: ")
branchTime=(Clock.Hour)
If branchTime>13 And branchTime<1 Then
  TextWindow.WriteLine("London Branch is CLOSED")
  EndIf
If branchTime>=1 and branchTime<=13 Then
  TextWindow.WriteLine ("London Branch is OPEN")
  EndIf
If branchTime>18 And branchTime<6 Then
  TextWindow.WriteLine("New York branch is CLOSED")
  EndIf
 If branchTime>=6 and branchTime<=18 Then
 TextWindow.WriteLine ("New York Branch is OPEN") 
 Endif
 If branchTime>23 And branchTime<9 Then
   TextWindow.WriteLine("Portland Branch is CLOSED")
   EndIf 
   if branchTime>=9 and branchTime<=21 Then
   TextWindow.WriteLine ("Portland Branch is OPEN")
   Endif
