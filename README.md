# RatingView

Simple android widget that can replace standard inconvenient RatingBar in your app.

##Description
The default Android `RatingBar` widget hardly can satisfy developers' needs. It's a pain to customize it at all. This simple view can take a huge advantage of setting and scaling drawables for rating view easily.

##Usage
You can download this library with the following line in your `app` module `build.gradle`:

```gradle
implementation 'com.github.Foysalofficial:rating-view:16.0'
```    
##Example
Declare `RatingView` in your XML with `app` attributes:

```xml
<com.ictfoysal.ratingview.RatingView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    app:drawable_empty="@drawable/ic_star_empty"
    app:drawable_filled="@drawable/ic_star_filled"
    app:drawable_half="@drawable/ic_star_half"
    app:drawable_margin="4dp"
    app:drawable_size="24dp"
    app:is_indicator="false"
    app:max_count="5"
    app:rating="3.5" />
```
And use it through `RatingView` instance in your code. Goog luck!
