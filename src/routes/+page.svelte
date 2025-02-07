
<script>
  import Button from "../lib/components/Button.svelte";
  import { base } from "$app/paths";
</script>

<div class="header">Financia</div>


<div class="welcome-container">
  <h1 class="welcome-message">Welcome to Financia! What are we learning today?</h1>
</div>


<div class="buttons">
  <button class="gradient-button" onclick="location.href='{base}/1'">The Nature and <br> Importance of Economics</button>
  <button class="gradient-button" onclick="location.href='{base}/2'">Supply <br> and Demand</button>
  <button class="gradient-button" onclick="location.href='{base}/4'">Multiple <br> Choice</button>
</div>


<div class="credits-container">
  <button class="credits-message" onclick="location.href='{base}/credits'">Credits</button>
</div>

<style>
    .header {
      background: linear-gradient(90deg, #6a11cb, #2575fc); /* Purple to blue gradient */
      color: white;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      text-align: left;
      font-size: 48px; /* Increased font size */
      padding: 20px;
      margin-bottom: 20px;
    }
  .credits-container {
    text-align: center;
    margin-top: 50px;
    margin-bottom: 20px;
  }
  .credits-message {
    font-size: 18px;
    color: #828282;
    background: none;
    border: none;
    cursor: pointer;
  }
  .credits-message:hover {
    text-decoration: underline;
  }
  .buttons {
    display: flex;
    flex-direction: row;
    gap: 20px;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Makes the container fill the viewport vertically */
  }
  .welcome-container {
    text-align: center;
    margin-top: 50px;
    margin-bottom: -300px
  }
  .welcome-message {
    font-size: 24px;
    color: #333;
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  }

  .gradient-button {
    font-size: 18px;
    padding: 30px 60px;
    border: none;
    border-radius: 8px;
    color: white;
    background: linear-gradient(90deg, #6a11cb, #2575fc); /* Same gradient as header */
    cursor: pointer;
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .gradient-button:hover {
    transform: scale(1.1);
    box-shadow: 0px 4px 10px rgba(106, 17, 203, 0.3);
  }
</style>