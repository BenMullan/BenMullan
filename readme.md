## Hello Darlings...

<style>
        @import url("https://fonts.googleapis.com/css2?family=Cabin:ital,wght@0,400..700;1,400..700&display=swap");
        
        html, body {
          height: 100vh;
        }
        
        body {
          text-align: center;
          font-family: "Cabin", sans-serif;
          font-weight: 400;
          margin: 0px;
          display: flex;
          flex-direction: column;
          flex-wrap: nowrap;
          justify-content: flex-start;
          align-items: center;
          align-content: center;
          row-gap: 0px;
          column-gap: 0px;
        }
        
        .item-bubbles-container {
          flex-grow: 1;
          flex-shrink: 0;
          flex-basis: auto;
          display: flex;
          flex-direction: row;
          flex-wrap: wrap;
          justify-content: center;
          align-items: flex-end;
          align-content: center;
          row-gap: 50px;
          column-gap: 150px;
        }
        
        .item-bubbles-container .item-bubble {
          flex-grow: 0;
          flex-shrink: 1;
          flex-basis: auto;
          text-decoration: none;
          color: #383838;
          transition: transform 0.1s;
        }
        
        .item-bubbles-container .item-bubble > img {
          width: 350px;
        }
        
        .item-bubbles-container .item-bubble:hover {
          transform: scale(1.05);
        }
        
        footer {
          flex-grow: 0;
          flex-shrink: 0;
          flex-basis: auto;
          color: #b3b3b3;
          margin: 10px;
        }
</style>

<main class="item-bubbles-container">
        
        <a class="item-bubble" href="https://benmullan.github.io/portfolio/">
                <img src="https://benmullan.github.io/assets/images/thumbnail-portfolio.png" />
                <h3>Portfolio</h3>
        </a>
        
        <a class="item-bubble" href="https://www.youtube.com/watch?v=OfOA4RKgIlA">
                <img src="https://benmullan.github.io/assets/images/thumbnail-graphpictures.png" />
                <h3>GraphPictures</h3>
        </a>
        
        <a class="item-bubble" href="https://github.com/BenMullan/witty-marketing-posters">
                <img src="https://benmullan.github.io/assets/images/thumbnail-witty-marketing-posters.png" />
                <h3>Witty Marketing Posters</h3>
        </a>

</main>

<footer>Ben Mullan © 2024</footer>
