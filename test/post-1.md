---

title: My Git it write page
menu_order: 1
post_status: publish
post_excerpt: This is a post excerpt
featured_image: https://dev.bootscore.me/wp-content/uploads/2013/03/soworthloving-wallpaper-1536x960.jpg


---

## My post content

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec a lacinia orci.
Nunc sodales massa enim, nec consectetur orci tempus ac.

### Section with image

![alt text for the image](/_images/pic4.jpg "Caption for the image")

Nam rutrum ultricies sapien id rhoncus. In pellentesque efficitur suscipit.
Aliquam vel est consectetur lectus malesuada mollis sit amet non neque. 

### Section with link

This is a [relative link](../sub-dir1/post3.md) which links to another markdown post w.r.t the current file.
This is an [absolute link](/folder1/sub-dir1/post3.md) which links to another post w.r.t the root directory.

### Section with HTML

<section id="home">
    <h2>Welcome to Our Website!</h2>
    <p>This is a sample HTML page with JavaScript and CSS styling.</p>
    <button type="button" onclick="showMessage()">Show message</button>
</section>

<script>
    function showMessage() {
        alert('Thank you for contacting us!');
    }
</script>

<!-- Sample CSS Style -->
<style>
    h1 {
        color: red;
    }
</style>

### Section with Shortcodes

### Code

```css
body {
  background-color: red !important;
}
```

```php
/**
 * Change navbar offcanvas title
 */
function change_navbar_offcanvas_title($title) {
  return 'My Menu';
}
add_filter('bootscore/offcanvas/navbar/title', 'change_navbar_offcanvas_title');
```

kkkkk