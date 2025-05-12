<svg xmlns="http://www.w3.org/2000/svg" width="600" height="300" viewBox="0 0 600 300" fill="none">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        * {
          margin: 0;
          padding: 0;
        }

        @keyframes text-effect-red-yellow {
          0%   { color: red; }
          50%  { color: #e9ee07; }
          100% { color: red; }
        }

        @keyframes cover-anim {
          0%   { background-color: rgba(0, 0, 0, 1); }
          100% { background-color: transparent; z-index: -1; }
        }

        .container {
          height: 300px;
          width: 100%;
          position: relative;
          display: flex;
          flex-direction: column;
          justify-content: center;
          align-items: center;
          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
          background: black;
        }

        .cover {
          position: absolute;
          top: 0;
          left: 0;
          width: 100%;
          height: 100%;
          z-index: 9999;
          background-color: rgba(0, 0, 0, 1);
          animation: cover-anim 1s ease forwards 2s;
        }

        .hero {
          position: absolute;
          color: white;
          text-align: center;
        }

        .hero h1 span {
          animation: text-effect-red-yellow 2s ease-in-out infinite;
        }

        .hero p {
          font-size: 1.1rem;
          margin-top: 0.5rem;
        }

      </style>

      <div class="container">
        <div class="cover"></div>
        <div class="hero">
          <h1>Hullo, I'm <span>Joan</span></h1>
          <p>I'm a programmer that's still has a lot to learn.</p>
          <p>My main focus is on system programming</p>
          <p>but I sometimes do full stack as my side projects</p>
        </div>
      </div>
    </div>
  </foreignObject>
</svg>
