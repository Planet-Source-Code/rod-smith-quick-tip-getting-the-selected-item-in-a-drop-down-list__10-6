<div align="center">

## Quick tip: Getting the selected item in a drop down list


</div>

### Description

If you're an old VB hand, here's a quick tip that will save you some frustration and get you started in VB.NET...
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Rod Smith](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/rod-smith.md)
**Level**          |Beginner
**User Rating**    |5.0 (10 globes from 2 users)
**Compatibility**  |VB\.NET
**Category**       |[Controls/ Forms/ Dialogs/ Menus](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/controls-forms-dialogs-menus__10-3.md)
**World**          |[\.Net \(C\#, VB\.net\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/net-c-vb-net.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/rod-smith-quick-tip-getting-the-selected-item-in-a-drop-down-list__10-6/archive/master.zip)





### Source Code

```
DropDownList.SelectedIndex = DropDownList.Items.IndexOf(New ListItem("ABC"))
or
DropDownList.SelectedItem.Text = "ABC"
```

