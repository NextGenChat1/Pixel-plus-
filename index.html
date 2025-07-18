# Pixel-plus-
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <title>PixelPulse</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <!-- Tailwind CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- Google Font -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">
  <!-- FontAwesome -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
  <style>body{font-family:'Inter',sans-serif}</style>
</head>
<body class="bg-slate-100 text-slate-800">

<!-- ===== Header ===== -->
<header class="bg-gradient-to-r from-indigo-600 to-purple-600 text-white p-6 shadow-lg">
  <h1 class="text-3xl font-bold">PixelPulse</h1>
  <p class="text-sm opacity-90">Daily quotes, poetry, tips, recipes & more...</p>
</header>

<!-- ===== Auto-Generated Cards ===== -->
<section class="p-4 grid gap-6 md:grid-cols-2 lg:grid-cols-3">

  <!-- Quotes -->
  <div class="bg-white rounded-xl shadow p-4">
    <h2 class="font-semibold mb-2 text-indigo-600">
      <i class="fas fa-quote-left"></i> Quote
    </h2>
    <p id="quoteText" class="italic"></p>
    <p id="quoteAuthor" class="text-xs text-right mt-2"></p>
  </div>

  <!-- Poetry -->
  <div class="bg-white rounded-xl shadow p-4">
    <h2 class="font-semibold mb-2 text-pink-600">
      <i class="fas fa-feather-alt"></i> Poetry
    </h2>
    <p id="poetryText" class="italic"></p>
  </div>

  <!-- Tips -->
  <div class="bg-white rounded-xl shadow p-4">
    <h2 class="font-semibold mb-2 text-green-600">
      <i class="fas fa-lightbulb"></i> Tip
    </h2>
    <p id="tipText"></p>
  </div>

  <!-- Recipe -->
  <div class="bg-white rounded-xl shadow p-4">
    <h2 class="font-semibold mb-2 text-orange-600">
      <i class="fas fa-utensils"></i> Recipe
    </h2>
    <p id="recipeTitle"></p>
  </div>

  <!-- News -->
  <div class="bg-white rounded-xl shadow p-4">
    <h2 class="font-semibold mb-2 text-red-600">
      <i class="fas fa-newspaper"></i> News
    </h2>
    <p id="newsHeadline"></p>
  </div>

</section>

<!-- ===== User Post Form ===== -->
<section class="p-4">
  <div class="max-w-lg mx-auto bg-white rounded-xl shadow p-6 space-y-4">
    <h2 class="text-xl font-semibold"><i class="fas fa-edit"></i> Add Your Post</h2>
    <form id="userForm" class="space-y-3">
      <select name="type" class="w-full border rounded px-3 py-2">
        <option>Quote</option>
        <option>Poetry</option>
        <option>Tip</option>
        <option>Recipe</option>
        <option>News</option>
      </select>
      <textarea name="text" placeholder="Write something..." class="w-full border rounded px-3 py-2" required></textarea>
      <button type="submit" class="bg-indigo-600 text-white px-4 py-2 rounded">Save</button>
    </form>

    <!-- Display Saved Posts -->
    <div id="savedPosts" class="mt-4 space-y-2 text-sm"></div>
  </div>
</section>

<script>
/* ===== Auto Data ===== */
const quotes = [
  "Stay hungry, stay foolish. — Steve Jobs",
  "Simplicity is the ultimate sophistication. — Leonardo da Vinci",
  "The best way to predict the future is to invent it. — Alan Kay"
];

const poetries = [
  "The moon whispers secrets to the silent sea...",
  "In every shadow, a story waits to be told.",
  "Stars write poems on the canvas of night."
];

const tips = [
  "Drink 8 glasses of water daily.",
  "Take a 5-minute break every hour while working.",
  "Read one page of a book before bed."
];

const recipes = [
  "Avocado Toast with Chili Flakes",
  "5-Minute Garlic Butter Pasta",
  "Berry-Banana Smoothie Bowl"
];

const news = [
  "AI writes its first novel, critics amazed.",
  "Breakthrough in battery tech promises 1000-mile EVs.",
  "Global summit on climate action begins today."
];

function pick(arr){return arr[Math.floor(Math.random()*arr.length)];}

document.getElementById('quoteText').textContent = pick(quotes);
document.getElementById('poetryText').textContent = pick(poetries);
document.getElementById('tipText').textContent = pick(tips);
document.getElementById('recipeTitle').textContent = pick(recipes);
document.getElementById('newsHeadline').textContent = pick(news);

/* ===== User Posts ===== */
const form = document.getElementById('userForm');
const list = document.getElementById('savedPosts');

function renderPosts(){
  const posts = JSON.parse(localStorage.getItem('posts')||'[]');
  list.innerHTML = posts.map(p=>`
    <div class="border-l-4 border-indigo-400 pl-2">
      <strong>${p.type}:</strong> ${p.text}
    </div>
  `).join('');
}

form.addEventListener('submit', e=>{
  e.preventDefault();
  const data = Object.fromEntries(new FormData(form));
  const posts = JSON.parse(localStorage.getItem('posts')||'[]');
  posts.unshift(data);
  localStorage.setItem('posts', JSON.stringify(posts));
  form.reset();
  renderPosts();
});
renderPosts();
</script>
</body>
</html>
