# PROGRAM-TO-PERFORM-ARITHMETIC-AND-DATE-LOGICAL-OPERATIONS
Private Sub CommandButton1_Click()
If (1 = 1) And (0 = 0) Then
MsgBox "AND evaluated to TRUE", vbOKOnly, "AND operator"
Else
MsgBox "AND evaluated to FALSE", vbOKOnly, "AND operator"
End If
End Sub

Private Sub CommandButton2_Click()
If (1 = 1) Or (5 = 0) Then
MsgBox "OR evaluated to TRUE", vbOKOnly, "OR operator"
Else
MsgBox "OR evaluated to FALSE",
vbOKOnly, "OR operator"
End If
End Sub
Private Sub CommandButton3_Click()
If Not (0 = 0) Then
MsgBox "NOT evaluated to TRUE", vbOKOnly, "NOT operator"
Else
MsgBox "NOT evaluated to FALSE", vbOKOnly, "NOT operator"
End If
End Sub
