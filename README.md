# Android-Frequently-Asked-Questions
## Android 异常
1.Calling startActivity() from outside of an Activity  context requires the FLAG_ACTIVITY_NEW_TASK flag. Is this really what you want?
> 错误代码     
context=getApplicationContext()
Intent intent = new Intent();
intent.setClass(context,XX.class);
context.startActivity(intent);
>   <b>解决方法： context=XXActivity即把getApplicationContext换为Activity内的context
##第三库经常出现的bug
  1. Glide
  >Java.lang.IllegalArgumentException:You cannot start a load for a destroyed activity  
  <b> 解决方法：Glide.with(getContext().getApplicationContext()).load(mImages.get(position)).into(imageView);</b>
  
##Android Studio 常见错误
##常规开发产生的错误
## 其他错误



