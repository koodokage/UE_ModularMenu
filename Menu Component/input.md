---
label: Input
order: 60
icon: "/static/trilogy.png"
---
# Input

Allows you to make safe key assignments for keyboard and gamepad

 -Input Bind Lists can be  `Procedural` or `Scripted`

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
 Folder :  `~/InputBind/Base`
:::

Add To Target Widget

:   Menu Layout
    
   : > The main layout of plugin
   : > Folder : Modular Menu/Widgets/WBP_MenuLayout

    - Select a  MC_`InputBindList` and add on the `Setting Menu` canvas and fit the size/scale/position


:   Tab Panel
    
   : > Layout component for main layout
   : > Folder : Modular Menu/Widgets/LayoutComponents/LC_TabPanel

    - Select  MC_`InputBindList` and add on the `MainContentPanel/AnyContent/VerticalBox


:   [!badge variant="light" corners="square" size="m" text="Setup"]()

    - Select after adding MC_`InputBindList`

    - In Details panel find `Saves` section change the save slot names for saving work 

    - In Details panel find `DefaultContexts` section and set default IMC datas  `[DefaultContexts data used for reset and default initializations]`
    
    - In Details panel find `MappableContexts` section and set runtime changable IMC datas `[MappableContexts data used for runtime input listening]`