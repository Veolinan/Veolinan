# 👋 Hi, I’m Veolinan
## 👀 I’m interested in Computer security and coding

## 📫 How to reach me
Email masigwafelix@gmail.com

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Auto-Loading Jokes</title>
</head>
<body>
  <div id="joke-container">
    <!-- Joke will be displayed here -->
  </div>

  <script>
    function fetchJoke() {
      // Fetch a new joke from the API or source
      fetch('https://readme-jokes.vercel.app/api')
        .then(response => response.json())
        .then(data => {
          document.getElementById('joke-container').innerHTML = data.joke;
        })
        .catch(error => console.error('Error fetching joke:', error));
    }

    // Initial load
    fetchJoke();

    // Set interval to load a new joke every 30 seconds
    setInterval(fetchJoke, 30000);
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
