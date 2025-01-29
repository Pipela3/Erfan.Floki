<!-- فقط برای وبسایت‌های شخصی قابل استفاده است -->
<a href="https://instagram.com/your_username" class="animated-button">
  <img src="instagram-icon.png" class="jump">
  <span>Follow Me</span>
</a>

<style>
.animated-button {
  animation: pulse 2s infinite;
}
.jump {
  animation: jump 0.8s ease-in-out infinite;
}
@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}
@keyframes jump {
  0%, 100% { transform: translateY(0); }
  50% { transform: translateY(-10px); }
}
</style>8
