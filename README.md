# - Первый репозиторий
### Какой-то код 
 private void Button_Click_1(object sender, RoutedEventArgs e)
 {
     if (Convert.ToInt32(T2.Text) >= 16 && Convert.ToInt32(T2.Text) <= 24) 
     {
         T1.Text = "Вечер";
     }
     else
     {

     };

     if (Convert.ToInt32(T2.Text) >= 00 && Convert.ToInt32(T2.Text) <= 4)
     {
         T1.Text = "Ночь";
     }
     else
     {

     };

     if (Convert.ToInt32(T2.Text) > 4 && Convert.ToInt32(T2.Text) <= 10)
     {
         T1.Text = "Утро";
     }
     else
     {

     };
     

     if (Convert.ToInt32(T2.Text) > 10 && Convert.ToInt32(T2.Text) < 16)
     {
         T1.Text = "День";
     }
     else
     {

     };
