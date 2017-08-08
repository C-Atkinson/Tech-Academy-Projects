# SimpleBasic-Sec-20-2
Below is the code I created to satisfy the Section requirements for the Branch availabitlity for Portland, New York and London


TextWindow.Title="Branch Availability"
TextWindow.ForegroundColor="Blue"
TextWindow.WriteLine("Branches have the following availability.: ")
branchTime=(Clock.Hour)
If branchTime>=1 and branchTime<=13 Then
  TextWindow.WriteLine ("London Branch is OPEN")
  EndIf
 If branchTime>=6 and branchTime<=18 Then
 TextWindow.WriteLine ("New York Branch is OPEN") 
 Endif
 If branchTime>=9 and branchTime<=21 Then
   TextWindow.WriteLine ("Portland Branch is OPEN")
 Else 
   TextWindow.WriteLine("No branches OPEN at this time.")
 EndIf
