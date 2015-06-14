Imports System.IO
Public Class Form1

    Private Sub Button1_Click(sender As Object, e As EventArgs) Handles Button1.Click
        ' Khai báo biến
        Dim A As Integer = txtA.Text
        Dim B As Integer = txtB.Text
        Dim Resul As String = Txt.Text


        ' Nhập giá trị vào Buttom Calculate
        Txt.Text = Val(txtA.Text) + Val(txtB.Text)

    End Sub
End Class
