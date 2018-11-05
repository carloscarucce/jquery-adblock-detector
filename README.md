# jQuery Adblock Detector

To use adblock detector, simply do as follows:

```html
<script src="jquery.adblock-detector.js"></script>
<script>
    $.adblockDetector.detect().done(function(adsEnabled){
        if (!adsEnabled) {
            //Ads are blocked
        }
    });
</script>
```

**Important:** This is a jQuery plugin. So jQuery is _required._

Have fun. =)
