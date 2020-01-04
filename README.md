# Welcome to HighPerformanceDamageText!

This is an article that introduce how to use the Unity Package **High Performance Damage Text** and compare performance with UGUI.

## How To Use

### Steps:
#### 1.Import damage text font files
![import_font_file](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/import_fonts.png)
#### 2.Edit damage text animation prefab
![edit_animation_prefab](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/edit_animation_prefab.png)
Duration:	animation time
Sprite Gap:	text sprite gap
**Font:		text font**
Curves:		animation curves(offset, alpha, scale)
#### 3.Set render camera and animation key
![animation_setting](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/render_camera.png)
**Culling Mask:	UI**
**Projection:		Orthographic**
![animation_setting](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/animation_setting.png)
Key:function param "key"
#### 4.Call function ShowDamageText(key, content, transform)
![call_function](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/call.png)

### video  tutorial
[click here](http://www.baidu.com)


## Performance Test
add 100 players and each player displays damage text every 0.2 seconds.

Show 100 damage text in a meantime
![call_function](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/show_damage_100.png)[HighPerformanceDamageText]
![call_function](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/show_damage_100_ugui.png)[UGUI]

Update damage text animation
![call_function](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/update_animation.png)[HighPerformanceDamageText]
![call_function](https://github.com/heikun288/HighPerformanceDamageText-Unity3D/blob/master/pic/update_animation_ugui.png)[UGUI]