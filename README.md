Created by http://planet.io

Zoink is a way to lazy load background images. Problem with most lazy load scrolling solutions is they work for <img>. But for responsive designed websites, there are multiple images for an element using background images. To lazy load content, you can use zoinked for backgroun images!

1. Add .zoinked css class for lazy loaded content
```
.zoinked #myBottomOfPageBgImage {
 background: url("/path/to/huge/image.jpg")
}
```

2. Load Zoinked JS
 ```
<script type="text/javascript" charset="utf-8">
  var zoink = new window.Zoink();
</script>
```
