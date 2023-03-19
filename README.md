
<svg fill="none" viewBox="0 0 800 400" width="600" height="300" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <div xmlns="http://www.w3.org/1999/xhtml">
      <style>
        @keyframes hi  {
            0% { transform: rotate( 0.0deg) }
           10% { transform: rotate(14.0deg) }
           20% { transform: rotate(-8.0deg) }
           30% { transform: rotate(14.0deg) }
           40% { transform: rotate(-4.0deg) }
           50% { transform: rotate(10.0deg) }
           60% { transform: rotate( 0.0deg) }
          100% { transform: rotate( 0.0deg) }
        }

        @keyframes gradient {
          0% {
            background-position: 0% 50%;
          }
          50% {
            background-position: 100% 50%;
          }
          100% {
            background-position: 0% 50%;
          }
        }

        .container {
          --color-main: #5452ee;
          --color-primary: #e73c7e;
          --color-secondary: #23a6d5;
          --color-tertiary: #ffff;

          background: linear-gradient(-45deg, var(--color-main), var(--color-primary), var(--color-secondary), var(--color-tertiary));
          background-size: 400% 400%;
          animation: gradient 15s ease infinite;

          width: 100%;
          height: 300px;

          display: flex;
          justify-content: center;
          align-items: center;
          color: white;

          font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol";
        }

        .hi {
          animation: hi 1.5s linear -0.5s infinite;
          display: inline-block;
          transform-origin: 70% 70%;
        }

        @media (prefers-color-scheme: light) {
          .container {
            --color-main: #F15BB5;
            --color-primary: #24b0ef;
            --color-secondary: #4526f6;
            --color-tertiary: #f6f645;
          }
        }

        @media (prefers-reduced-motion) {
          .container {
            animation: none;
          }

          .hi {
            animation: none;
          }
        }
      </style>

      <div class="container">
        <h1>
        Hello <img height="50" width="50" src="https://github.githubassets.com/images/mona-whisper.gif" /> I'm Jamie <div class="hi">👋</div></h1>
      </div>
    </div>
  </foreignObject>
</svg>


Recents:
  - [app-layout](https://github.com/jsmithdev/app-layout) - My app layout component(s) for LWC apps (current WIP)
  - [generator-lwc-app](https://github.com/jsmithdev/generator-lwc-app) - My yeoman generator to easily create an LWC PWA
  - [Ourss](https://github.com/jsmithdev/ourss) - My podcast PWA @ <https://ourss.app> (my forever WIP 🙃)
  - [Reapo](https://github.com/jsmithdev/reapo) - My repository manager (linux)
  - [Component Land](https://component.land) - App to distribute lightning web components, Salesforce soutions, etc
  - [dir2dir](https://www.npmjs.com/package/dir2dir) - CLI tool to copy a directory to a renamed directory while renaming matching child files
  - [img2txt](https://www.npmjs.com/package/imgtxt) - Fun CLI tool to output text from an image
  - [SOQE](https://marketplace.visualstudio.com/items?itemName=jamiesmiths.soqe) - My Salesforce Object Query Extension (saké)(vs code extension)
  - [Abyski](https://marketplace.visualstudio.com/items?itemName=jamiesmiths.abyski) - My take on abyss + monokai (vs code theme)
 
 ---

<p align="center">


<img width="460" height="300" src="https://github-readme-streak-stats.herokuapp.com/?user=jsmithdev&stroke=ffffff&background=1c1917&ring=0891b2&fire=0891b2&currStreakNum=ffffff&currStreakLabel=0891b2&sideNums=ffffff&sideLabels=ffffff&dates=ffffff&hide_border=true"/>

</p>

<!-- ![genie beanie](https://i.imgur.com/myAHVLP.jpg) -->
