# Labelme-Polygons
 
# 因项目需要标注倾斜矩形物体，看到Github没有可以直接Fork的，所以魔改了大神的[labelme](https://github.com/wkentaro/labelme)项目。

## Pre
1.主程序放置于labelme/main.exe中，解压Label_V2整个文件夹后，双击exe文件即可运行label程序。 

2.将标注的图片(.jpg/.png)放置于Picture_Data中，便于标注以及读取文件。 

## Using
### 1.点击Open或Open Dir
（如需大量标记图片建议批量放在Picture_Data文件夹中 点击Open Dir）

### 2.标注
![image](https://github.com/For-LD/Labelme-Polygons/blob/main/source/1.png)
1）	可选择菜单栏Edit选择标注Rectangles(正矩形)，Polygons(斜矩形)，Points(点)

2）	或者可以使用快捷按键Rectangles(Ctrl+R)，Polygons (Ctrl+N)

#### Rectangles：
![image](https://github.com/For-LD/Labelme-Polygons/blob/main/source/2.png)
点完第一个点松开鼠标滑动至令一标注边缘点击鼠标即可完成标注。

#### Polygons：
![image](https://github.com/For-LD/Labelme-Polygons/blob/main/source/3.png)

![image](https://github.com/For-LD/Labelme-Polygons/blob/main/source/4.png)

标注顺序：永远先点击左上角为1，然后点击右上角为2，最后点击右下角为3（如上所示），程序会自动拟合出与之匹配的斜矩形。

### 3.保存
点击Save或者(Ctrl+S)即可跳出以下界面

![image](https://github.com/For-LD/Labelme-Polygons/blob/main/source/5.png)

点击保存即可保存json标注文件。

## PS.快捷键
```
close: Ctrl+W
open: Ctrl+O
open_dir: Ctrl+U
quit: Ctrl+Q
save: Ctrl+S
save_as: Ctrl+Shift+S
save_to: null
delete_file: Ctrl+Delete

open_next: [D, Ctrl+Shift+D]
open_prev: [A, Ctrl+Shift+A]

create_polygons: Ctrl+N
create_rectangle: Ctrl+R

edit_polygon: Ctrl+J
delete_polygon: Delete
duplicate_polygon: Ctrl+D
undo: Ctrl+Z
add_point_to_edge: Ctrl+Shift+P
edit_label: Ctrl+E
edit_line_color: Ctrl+L
edit_fill_color: Ctrl+Shift+L
toggle_keep_prev_mode: Ctrl+P

```
