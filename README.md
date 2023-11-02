<br />

- 👋 Hi! This is Spooky's Github profile
- 🎉 I'm 16 years old
- ![](https://komarev.com/ghpvc/?username=SpookyGS&color=red)
  
## Languages
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SpookyGS&theme=tokyonight&langs_count=8)](https://github.com/anuraghazra/github-readme-stats)
## Github Stats
[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=SpookyGS&count_private=true&show_icons=true&theme=tokyonight)](https://github.com/anuraghazra/github-readme-stats)
## Discord Profile
const getDiscord = count => 'yuliss03'.repeat(count);

const button = document.createElement('button');
button.textContent = 'yuliss03';
button.style.fontSize = '40px';
document.body.appendChild(button);

let i = 1;
button.addEventListener('click', () => {
  window.copyTextToClipboard(getDiscord(i));
  button.textContent = `Copy ${getDiscord(++i)}`;
});
