# 👋 Hi, I’m Veolinan
## 👀 I’m interested in Computer security and coding

## 📫 How to reach me
Email masigwafelix@gmail.com

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Refreshing Joke</title>
</head>
<body>

<div id="joke-container" style="display: flex;"></div>

<script>
function fetchJoke() {
    // Fetch the joke content and update the #joke-container
    fetch('https://readme-jokes.vercel.app/api')
        .then(response => response.json())
        .then(data => {
            const jokeContainer = document.getElementById('joke-container');
            jokeContainer.innerHTML = data.html;
        })
        .catch(error => console.error('Error fetching joke:', error));
}

// Initial fetch when the page loads
fetchJoke();

// Refresh the joke every 5 seconds
setInterval(fetchJoke, 5000);
</script>

</body>
</html>



<div style="display: flex;">

  <div style="flex: 50%; padding: 10px;">
    <h2>📊 My GitHub Stats</h2>
    <img src="https://github-readme-stats.vercel.app/api?username=Veolinan&show_icons=true" alt="GitHub Stats" />
  </div>

  <div style="flex: 50%; padding: 10px;">
    <h2>📈 Most Used Languages</h2>
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Veolinan&theme=blue-green" alt="Most Used Languages" />
  </div>

</div>

## 👁️ Profile Views
![Profile View Counter](https://komarev.com/ghpvc/?username=Veolinan)
