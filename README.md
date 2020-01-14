# Welcome to HighPerformanceDamageText!

This is an article that introduce how to use the **Unity Package** [High Performance Damage Text](http://u3d.as/1HLg) and compare performance with UGUI.

## How To Use

### video  tutorial
[click here](https://www.youtube.com/watch?v=I2VnSVcpiPo&feature=youtu.be)

### Steps:
#### 1.Import damage text font files
![import_font_file](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/import_fonts.png)
#### 2.Edit damage text animation prefab
![edit_animation_prefab](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/edit_animation_prefab.png)
#### 3.Set render camera and animation key
![animation_setting](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/render_camera.png)
![animation_setting](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/animation_setting.png)
#### 4.Call function ShowDamageText(key, content, transform)
![call_function](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/call.png)

### Render Order
#### order in damage texts
![sorting_order_1](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_1.png)
exp > attack > hit


![sorting_order_2](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_2.png)
hit > exp > attack
#### order in ui
![sorting_order_with_ui_1](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_with_ui_1.png)
![sorting_order_with_ui_2](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_with_ui_2.png)
hit > exp > attack > ui picture


![sorting_order_with_ui_3](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_with_ui_3.png)
hit > exp > ui picture > attack


![sorting_order_with_ui_4](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_with_ui_4.png)
hit > ui picture > exp > attack


![sorting_order_with_ui_5](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/sorting_order_with_ui_5.png)
ui picture > hit > exp > attack


## Performance Test
add 100 players and each player displays damage text every 0.2 seconds.

Show 100 damage text in a meantime

[HighPerformanceDamageText]
![show_damage_100](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/show_damage_100.png)
[UGUI]
![show_damage_100_ugui](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/show_damage_100_ugui.png)

Update damage text animation

[HighPerformanceDamageText]
![update_animation](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/update_animation.png)
[UGUI]
![update_animation_ugui](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/update_animation_ugui.png)

## Update
### Support screen space
![screen_space](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/screen_space.png)