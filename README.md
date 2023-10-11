# WPF-DEMO

Il faut récupérer la DLL de YCalendar puis aller sur dépendances -> Ajouter une référence de projet et enfin cliqué sur YCalendar-WPF

Pour l'utilisé il faut ajouter dans la vue :  xmlns:YC="clr-namespace:YCalendar_WPF.Views;assembly=YCalendar-WPF"
et pour l'utiliser dans la vue il faut simplement faire <YC:YCalendarControl />

Vue = une fenêtre window dans lequel il va être appelé

Exemple : 

<Window x:Class="WPF_DEMO.MainWindow"
        xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
        xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
        xmlns:d="http://schemas.microsoft.com/expression/blend/2008"
        xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006"
        xmlns:local="clr-namespace:WPF_DEMO"
        xmlns:YC="clr-namespace:YCalendar_WPF.Views;assembly=YCalendar-WPF"
        mc:Ignorable="d"
        Title="MainWindow" Height="450" Width="800">
    
    <Grid>
        <YC:YCalendarControl/>
    </Grid>
</Window>