
<html>
    <script type="text/javascript">
        function image(img) {
            var src = img.src;
            console.log(src)
            if(src.includes("Boat.gif")){
                img.src="dog.gif"
            }
            else{
                img.src="Rocket.gif"
            }
        }
    </script>
    <img src="Boat.gif" onclick="image(this)">
</html>
