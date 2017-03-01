# Alerter with image loading from url

This is my fork of [Alerter](https://github.com/Tapadoo/Alerter) library by [Tapadoo](https://github.com/Tapadoo) that enables you to set icon to url of an image in a CircleView and make it round.


Added dependencies:
- [Glide](https://github.com/bumptech/glide)
- [RoundedImageView](https://github.com/vinc3m1/RoundedImageView)

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
     * Set the Alert's Icon Round, false by default
     * @param value True to be round, false to be regular
     * @return This Alerter
     */
    public Alerter setRounded(boolean value)
```

Additional changes:

Set pulsing to false by default
```java
private boolean enableIconPulse = false;
```
