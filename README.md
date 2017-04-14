# Alerter with image loading from url

This is my fork of [Alerter](https://github.com/Tapadoo/Alerter) library by [Tapadoo](https://github.com/Tapadoo) that enables you to set icon to url of an image and change the text color.


Added dependencies:
- [Glide](https://github.com/bumptech/glide)

Added methods:
```java
/**
     * Set the Alert's Icon
     *
     * @param url The Image's URL
     * @return This Alerter
     */
    public Alerter setIcon(final String url)
```

```java
/**
     * Set Alert's text color
     *
     * @param colorId The color's resource id
     * @return This Alerter
     */
    public Alerter setTextColor(@ColorRes final int colorId)
```


Additional changes:

Set pulsing to false by default
```java
private boolean enableIconPulse = false;
```
