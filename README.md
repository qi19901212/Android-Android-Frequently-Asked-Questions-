# Android-Frequently-Asked-Questions
##第三库经常出现的bug
  1. Glide
  >Java.lang.IllegalArgumentException:You cannot start a load for a destroyed activity  
  <b> 解决方法：Glide.with(getContext().getApplicationContext()).load(mImages.get(position)).into(imageView);</b>
  
##Android Studio 常见错误
##常规开发产生的错误
## 其他错误



