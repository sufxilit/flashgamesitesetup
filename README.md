<html>
<head>
<script src="https://unpkg.com/@ruffle-rs/ruffle"></script>
<style>
html, body {
margin:0px;
}
</style>
</head>
<body>
<script>
window.RufflePlayer = window.RufflePlayer || {};
//Below code forces autoplay, no splashscreen and allows sound

window.RufflePlayer.config = {
"autoplay": "on","splashScreen": false,"unmuteOverlay": "hidden","quality": "medium" };
// End custom configuration code above
window.addEventListener("load", (event) => {
const ruffle = window.RufflePlayer.newest();
const player = ruffle.createPlayer();
const container = document.getElementById("container");
container.appendChild(player);
player.load("https://sufxilit.github.io/iweoujfhniw/papascheeseria_102.swf");
player.style.width = "100%";
player.style.height = "100%";
});
</script>
<div id="container"></div>
</body>
</html>
