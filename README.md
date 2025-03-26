# Welcome to My GitHub Profile

![Animated Background](https://source.unsplash.com/random/1600x900)

## About Me
Hi there! Welcome to my GitHub profile. Enjoy your stay! 🎶

---

## 🎵 Backsound
<audio autoplay loop>
    <source src="your-song.mp3" type="audio/mpeg">
</audio>

---

## 🔘 Interactive Buttons

### ❤️ For You
<button onclick="showPopup('popup1')">For You</button>
<div id="popup1" style="display:none;">
    <img src="https://cdn-icons-png.flaticon.com/512/833/833472.png" alt="Heart" width="100">
</div>

### 🕵️ My Secret
<button onclick="showPopup('popup2')">My Secret</button>
<div id="popup2" style="display:none;">
    <img src="https://cdn-icons-png.flaticon.com/512/1305/1305386.png" alt="Hacking" width="100">
</div>

### 💖 I Love You
<button onclick="showPopup('popup3')">I Love You</button>
<div id="popup3" style="display:none;">
    <p>I'm so grateful to have you in my life, I love you ❤️</p>
</div>

---

## 📜 JavaScript for Popups
```html
<script>
    function showPopup(id) {
        var popup = document.getElementById(id);
        popup.style.display = 'block';
        setTimeout(() => popup.style.display = 'none', 3000);
    }
</script>
```

---

Enjoy exploring my profile! 🚀
