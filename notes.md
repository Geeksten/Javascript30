## Notes taken during the JavaScript30 study
### 1. JavaScript Drum Kit
* Explore how to add an event listener
    - use this for figuring out the key-codes used in the final html file
    - open up the console to see the keyboard event details

 - ```
    <script>
  window.addEventListener('keydown', function(e) {
  console.log(e);
});
</script>
    ```