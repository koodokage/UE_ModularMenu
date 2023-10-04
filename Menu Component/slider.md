---
label: Slider
order: 89
icon: "/static/slider.png"
---

# Slider

Allows you to make precise settings between certain values

 -Sliders can be `Radial` or `Straight`


# Setting

<style>
    .sample {
        text-align: center;
        color: #1956AF;
        border-radius: 10px;
        background-color: #ffb300;
        border: 1px solid #1956AF;
        padding-top: 20px;
        margin-bottom: 20px;
    }
</style>

:::sample
 Folder :  `~/Sliders`
:::

Add To Target Widget

:   Menu Layout
    
   : > The main layout of plugin
   : > Folder : Modular Menu/Widgets/WBP_MenuLayout

    - Select a Slider MenuComponent and add on the `Setting Menu` canvas and fit the size/scale/position


:   Tab Panel
    
   : > Layout component for main layout
   : > Folder : Modular Menu/Widgets/LayoutComponents/LC_TabPanel

    - Select a Slider MenuComponent and add on the `MainContentPanel/AnyContent/VerticalBox
    - Before adding follow this step : 
    - `Duplicate any of Size Boxs`
    - `change the MC_Component with your selected component`
    - `For allignment change the Scale Box padding Right`


:   [!badge variant="light" corners="square" size="m" text="Setup"]()

    - Select after adding MC_`{YourSelectedSlider}`

    - In Details panel find `SlotName` change the save slot name for saving work 
    
    - In Details panel find `DefaultValue` its show the default sensitive value of setting