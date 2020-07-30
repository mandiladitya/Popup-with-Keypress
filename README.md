# Popup-with-Keypress
Popup &amp; Alert on Key Pressing 

```

<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
 <script>
    $(document).keydown(function(e) {
    // ESCAPE key pressed
    if (e.keyCode == 27) {
        window.alert("HELLO");
    }
 if (e.keyCode == 13) {
        window.alert("HELLO Enter");
    }

});
</script>

```
#### For Keycode of Keyboard
Visit to https://keycode.info/
