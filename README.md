# Steps to Add Snowfall Effect to your Website

1.Include the snow flurry and jquery script along with jQuery in the document header

`<script src="/jquery.min.js"></script>`
`<script src="h5ab-snow-flurry.js"></script>`

2.Add the following jQuery code in the footer of your HTML document right before the closing body tag

`<script>
jQuery(document).ready(function($){
$(document).snowFlurry({
maxSize: 5,
numberOfFlakes: 50,
minSpeed: 10,
maxSpeed: 15,
color: '#fff',
timeout: 0
});
});
</script>`

3.Add the following CSS just before the closing head tag (or you can also add this CSS in your stylesheet without using the style tag)

`<style>
.sf-snow-flake {
position: fixed;
top: -20px;
z-index: 99999;
}
.sf-snow-anim {
top: 110%;
}
</style>`

That’s it, save your HTML document and check out how awesome the snowfall effect looks. You can add more snowflakes by changing numberOfFlakes value in the jquery code, you can also control the speed of snowfall by modifying minSpeed and maxSpeed values.

>Coded By © [Zion Ashirwada](https://github.com/zionashirwada)
