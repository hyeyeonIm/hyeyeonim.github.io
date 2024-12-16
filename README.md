# hyeyeonim.github.io

<div id="language-toggle">
  <button onclick="toggleLanguage()">🌐 KR/EN</button>
</div>

<div id="korean-content" class="content">
  # 안녕하세요
  현재 한국어로 보고 계십니다.
  <!-- Add your Korean content here -->
</div>

<div id="english-content" class="content" style="display: none;">
  # Hello
  You are currently viewing in English.
  <!-- Add your English content here -->
</div>

<style>
.content {
  margin-top: 20px;
}

#language-toggle {
  position: fixed;
  top: 20px;
  right: 20px;
}

#language-toggle button {
  padding: 8px 16px;
  border: 1px solid #ddd;
  border-radius: 4px;
  background-color: white;
  cursor: pointer;
}

#language-toggle button:hover {
  background-color: #f0f0f0;
}
</style>

<script>
function toggleLanguage() {
  const koreanContent = document.getElementById('korean-content');
  const englishContent = document.getElementById('english-content');
  
  if (koreanContent.style.display === 'none') {
    koreanContent.style.display = 'block';
    englishContent.style.display = 'none';
  } else {
    koreanContent.style.display = 'none';
    englishContent.style.display = 'block';
  }
}
</script>