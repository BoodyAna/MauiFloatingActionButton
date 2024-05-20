# MauiFloatingActionButton

A reusable Floating Action Button (FAB) control for .NET MAUI using Material Icons.

## Usage

1. Add the `FloatingActionButton` control to your project.
2. Use the control in your XAML pages.

### Example

```xaml
<?xml version="1.0" encoding="utf-8" ?>
<ContentPage xmlns="http://schemas.microsoft.com/dotnet/2021/maui"
             xmlns:x="http://schemas.microsoft.com/winfx/2009/xaml"
             xmlns:local="clr-namespace:MauiFloatingActionButton.Controls"
             x:Class="MauiFloatingActionButton.Pages.MainPage">

    <Grid>
        <!-- Your main content goes here -->
        <CollectionView>
            <!-- CollectionView content -->
        </CollectionView>

        <!-- Floating Action Button -->
        <local:FloatingActionButton
            x:Name="fab"
            Clicked="OnFabClicked"/>
    </Grid>
</ContentPage>
