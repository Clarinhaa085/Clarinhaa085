html {
  --background-header: darkorchid;
  --color-header: white;
  --background-footer: coral;
  --color-footer: black;
  --background-main: white;
  --color-main: black;
}

html[data-theme="dark"] {
  --background-header: #121212;
  --color-header: lightgrey;
  --background-footer: #121212;
  --color-footer: lightgrey;
  --background-main: #121212;
  --color-main: lightgrey;
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  transition: all 0.3s;
}

header{
  height: 100px;
  background-color: var(--background-header);
  color: var(--color-header);
  display: flex;
  align-items: center;
  justify-content: space-evenly;
  margin-bottom: 20px;
}

main {
  padding: 20px 50px;
  background-color: var(--background-main);
  color: var(--color-main)
}

p {
  font-size: 1.2rem;
  margin-bottom: 1rem;
}

footer {
  height: 80px;
  background-color: var(--background-footer);
  color: var(--color-footer);
  display: flex;
  align-items: center;
  justify-content: center;
}
