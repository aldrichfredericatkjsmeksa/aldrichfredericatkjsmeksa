<!-- 
  HOW TO USE THIS TEMPLATE:
  1. Create a new repository with the same name as your GitHub username
  2. Add this code to your README.md file
  3. Upload your 'anime_background.gif' to the repository
  4. Adjust the text and links as needed
-->

<div align="center">
  <!-- Background GIF container with overlay -->
  <div style="
    position: relative;
    width: 100%;
    min-height: 400px;
    background-image: url('anime_background.gif');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    border-radius: 15px;
    overflow: hidden;
    box-shadow: 0 10px 20px rgba(0,0,0,0.3);
  ">
    <!-- Semi-transparent overlay for better text readability -->
    <div style="
      position: absolute;
      top: 0;
      left: 0;
      right: 0;
      bottom: 0;
      background: rgba(0, 0, 0, 0.5);
    "></div>
    
    <!-- Profile content container -->
    <div style="
      position: relative;
      z-index: 1;
      padding: 30px;
      color: white;
      text-align: center;
    ">
      <!-- Introduction section -->
      <h1 style="
        font-family: 'Arial Rounded MT Bold', 'Segoe UI', sans-serif;
        font-size: 2.5rem;
        margin-bottom: 20px;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.5);
        color: #ff6b9e;
      ">
        Konnichiwa! I'm <Your Name> ✨
      </h1>
      
      <p style="
        font-family: 'Comic Sans MS', cursive, sans-serif;
        font-size: 1.2rem;
        max-width: 700px;
        margin: 0 auto 30px;
        line-height: 1.6;
        background: rgba(0, 0, 0, 0.6);
        padding: 20px;
        border-radius: 10px;
        border-left: 4px solid #ff6b9e;
      ">
        A passionate developer who loves anime and coding! 
        By day I build web applications, by night I watch anime and work on personal projects. 
        Let's create something amazing together!
      </p>
      
      <!-- Programming languages section -->
      <h2 style="
        font-family: 'Arial Rounded MT Bold', 'Segoe UI', sans-serif;
        font-size: 1.8rem;
        margin: 30px 0 15px;
        color: #6bd6ff;
      ">
        My Tech Stack
      </h2>
      
      <div style="
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        gap: 25px;
        margin-bottom: 20px;
      ">
        <!-- Python -->
        <div style="
          background: rgba(255, 255, 255, 0.9);
          padding: 10px 15px;
          border-radius: 50px;
          display: flex;
          align-items: center;
          box-shadow: 0 4px 8px rgba(0,0,0,0.2);
          transition: transform 0.3s;
        " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="30" height="30" alt="Python" />
          <span style="margin-left: 8px; color: #3776ab; font-weight: bold;">Python</span>
        </div>
        
        <!-- HTML -->
        <div style="
          background: rgba(255, 255, 255, 0.9);
          padding: 10px 15px;
          border-radius: 50px;
          display: flex;
          align-items: center;
          box-shadow: 0 4px 8px rgba(0,0,0,0.2);
          transition: transform 0.3s;
        " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" width="30" height="30" alt="HTML" />
          <span style="margin-left: 8px; color: #e34f26; font-weight: bold;">HTML</span>
        </div>
        
        <!-- JavaScript -->
        <div style="
          background: rgba(255, 255, 255, 0.9);
          padding: 10px 15px;
          border-radius: 50px;
          display: flex;
          align-items: center;
          box-shadow: 0 4px 8px rgba(0,0,0,0.2);
          transition: transform 0.3s;
        " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" width="30" height="30" alt="JavaScript" />
          <span style="margin-left: 8px; color: #f7df1e; font-weight: bold;">JavaScript</span>
        </div>
        
        <!-- CSS -->
        <div style="
          background: rgba(255, 255, 255, 0.9);
          padding: 10px 15px;
          border-radius: 50px;
          display: flex;
          align-items: center;
          box-shadow: 0 4px 8px rgba(0,0,0,0.2);
          transition: transform 0.3s;
        " onmouseover="this.style.transform='scale(1.1)'" onmouseout="this.style.transform='scale(1)'">
          <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" width="30" height="30" alt="CSS" />
          <span style="margin-left: 8px; color: #1572b6; font-weight: bold;">CSS</span>
        </div>
      </div>
      
      <!-- Social links -->
      <div style="margin-top: 30px;">
        <a href="https://github.com/yourusername" target="_blank" style="
          display: inline-block;
          margin: 0 10px;
          padding: 10px 20px;
          background: linear-gradient(45deg, #ff6b9e, #6bd6ff);
          color: white;
          text-decoration: none;
          border-radius: 50px;
          font-weight: bold;
          transition: transform 0.3s, box-shadow 0.3s;
          box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        " onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.3)'" 
           onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 4px 8px rgba(0,0,0,0.2)'">
          GitHub
        </a>
        <a href="https://linkedin.com/in/yourusername" target="_blank" style="
          display: inline-block;
          margin: 0 10px;
          padding: 10px 20px;
          background: linear-gradient(45deg, #6bd6ff, #ff6b9e);
          color: white;
          text-decoration: none;
          border-radius: 50px;
          font-weight: bold;
          transition: transform 0.3s, box-shadow 0.3s;
          box-shadow: 0 4px 8px rgba(0,0,0,0.2);
        " onmouseover="this.style.transform='scale(1.05)'; this.style.boxShadow='0 6px 12px rgba(0,0,0,0.3)'" 
           onmouseout="this.style.transform='scale(1)'; this.style.boxShadow='0 4px 8px rgba(0,0,0,0.2)'">
          LinkedIn
        </a>
      </div>
    </div>
  </div>
  
  <!-- Stats section -->
  <h2 style="
    font-family: 'Arial Rounded MT Bold', 'Segoe UI', sans-serif;
    font-size: 1.8rem;
    margin: 40px 0 20px;
    color: #ff6b9e;
  ">
    My GitHub Stats
  </h2>
  
  <div style="
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
  ">
    <img src="https://github-readme-stats.vercel.app/api?username=yourusername&show_icons=true&theme=radical" alt="GitHub Stats" style="border-radius: 10px;" />
    <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=yourusername&layout=compact&theme=radical" alt="Top Languages" style="border-radius: 10px;" />
  </div>
  
  <!-- Footer with anime quote -->
  <div style="
    margin-top: 40px;
    padding: 20px;
    background: linear-gradient(90deg, rgba(107,214,255,0.2), rgba(255,107,158,0.2));
    border-radius: 10px;
    font-style: italic;
  ">
    <p style="margin: 0; font-size: 1.1rem;">
      "It's not the face that makes someone a hero, it's the heart." - All Might (My Hero Academia)
    </p>
  </div>
</div>
