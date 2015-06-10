# LoweImageView
一个简单的自定义view,能够在布局的时候指定imageview的宽高比例
## Example

```xml
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
              xmlns:app="http://schemas.android.com/apk/res-auto"
              android:layout_width="match_parent"
              android:layout_height="match_parent"
              android:orientation="vertical">

    <cn.sz.leonhardt.loweimageview.loweimageview_library.LoweImageView
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            app:ratio="2.3"
            android:scaleType="fitXY"
            android:src="@drawable/cat"/>
</LinearLayout>
```
## Usage

extends imageview
所以其他用法毫无区别

## Building in IntelliJ

Via Gradle:

```
not now
compile ''
```
## Building in Eclipse

![Go home you're drunk](http://img2.wikia.nocookie.net/__cb20130819142928/cardfight/images/thumb/5/55/Go-home-youre-drunk.jpg/500px-Go-home-youre-drunk.jpg)

## License

* 你喜欢对这代码做什么就做什么吧【表情】
