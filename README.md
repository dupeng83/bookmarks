# 仿twitter 网站

这是跟随PACKT出版的书 [Django by Example](http://djangobyexample.com/) 所做的仿twitter网站

运行 `git clone https://github.com/dupeng83/bookmarks` 克隆以后运行下列命令:

`cd bookmarks`

`virtualenv my_env`

`source my_env/bin/activate`

`pip install Django==1.8.6`

`pip install Pillow==2.9.0`

`pip install sorl-thumbnail==12.3`

`python manage.py migrate`

`python manage.py runserver`

登录以后在/account/ 页面上有一个 “BOOKMARK IT!”按钮，将这个按钮拖放到浏览器的工具栏里面

之后在浏览其它网站时，就可以点击这个工具栏上的“BOOKMARK IT!”按钮，当前网页中（足够大的）图片就会被单独显示出来，选中自己想要bookmark的图片，添加标题和描述之后就可以将其“bookmark”,也就是类似于发微博一样发在本网站中。

除此之外就是和twitter类似的功能：查看其它用户（“people”页面）以及follow和unfollow的功能
