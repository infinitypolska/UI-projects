using InfinityOS.Class;
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows;
using System.Windows.Controls;
using System.Windows.Data;
using System.Windows.Documents;
using System.Windows.Input;
using System.Windows.Media;
using System.Windows.Media.Effects;
using System.Windows.Media.Imaging;
using System.Windows.Navigation;
using System.Windows.Shapes;

namespace InfinityOS
{
    /// <summary>
    /// Interaction logic for MainWindow.xaml
    /// </summary>
    public partial class MainWindow : Window
    {
        public MainWindow()
        {
            InitializeComponent();
        }

        private void Window_MouseDown(object sender, MouseButtonEventArgs e)
        {
            //To move our window on mouse down
            if (e.ChangedButton == MouseButton.Left)
                DragMove();
        }



        private void Window_Loaded(object sender, RoutedEventArgs e)
        {
            DataContext = new WindowBlureffect(this, AccentState.ACCENT_DISABLED) { BlurOpacity = 110 };

        }

        private void ComboBox_SelectionChanged(object sender, SelectionChangedEventArgs e)
        {
            switch (c.SelectedIndex)
            {
                case 0:
                    DataContext = new WindowBlureffect(this, AccentState.ACCENT_DISABLED) { BlurOpacity = 100 };
                    break;
                case 1:
                    DataContext = new WindowBlureffect(this, AccentState.ACCENT_ENABLE_GRADIENT) { BlurOpacity = 100 };
                    break;
                case 2:
                    DataContext = new WindowBlureffect(this, AccentState.ACCENT_ENABLE_TRANSPARENTGRADIENT) { BlurOpacity = 100 };
                    break;
                case 3:
                    DataContext = new WindowBlureffect(this, AccentState.ACCENT_ENABLE_BLURBEHIND) { BlurOpacity = 100 };
                    break;
                case 4:
                    DataContext = new WindowBlureffect(this, AccentState.ACCENT_ENABLE_ACRYLICBLURBEHIND) { BlurOpacity = 100 };
                    break;
            }


        }

        private void Button_Click(object sender, RoutedEventArgs e)
        {

        }

        private void Create_account_TouchDown(object sender, TouchEventArgs e)
        {
            MessageBox.Show("test");
        }



        private void Label1_MouseDown(object sender, MouseButtonEventArgs e)
        {


           
        }

        private void TextBlock_MouseDown(object sender, MouseButtonEventArgs e)
        {

            Newaccount ca = new Newaccount();
            ca.Show();
            this.Close();
        }

        private void Window_Drop(object sender, DragEventArgs e)
        {

        }

        private void Button_Click_1(object sender, RoutedEventArgs e)
        {

        }

        private void Add_account_MouseHover(object sender, MouseEventArgs e)
        {

        }

        private void Add_account_MouseDown(object sender, MouseButtonEventArgs e)
        {
            Newaccount ca = new Newaccount();
            ca.Show();
            this.Close();
        }
    }
}
