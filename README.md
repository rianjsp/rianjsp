[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=900&size=23&pause=1000&color=5D02F7&random=false&width=435&lines=Hello!+I+Am+Rian+Ramos)](https://git.io/typing-svg)

👨🏻‍💻 **Estudante de Programação**

🏢 Mineirim trabalhando atualmente p/ Unimed, buscando oportunidades na área tec!

### Infos Academicas
- 👨🏻‍🎓 **Cursando Desenvolvimento de Sistemas Full Stack `Estácio`**
- 💻 **Certificação Practicioner AWS Cloud `AWS | KASolution | Estácio`**
- 💻 **Certificação adquirida em SOFT SKILLS `DANKICODE`**
- 💻 **Tecnologias que mais utilizo**: 
   - ![JavaScript](https://img.shields.io/badge/-JavaScript-yellow)
   - ![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white)
   - ![Vue.js](https://img.shields.io/badge/-Vue.js-green)
   - ![Python](https://img.shields.io/badge/-Python-blue)

### Tecs com afinidade:
- Axios, Express. (Para requisições, criar api's...)
- Vue, Vite. (Duas tecs front que ando utilizando bastante...)
- Bootstrap + Tailwind CSS. (Estas libs front são vida <3)
- React, Next. (Dois frameworks que ando estudando bastante)
- Python. `no geral` (Como não amar python?)
- TypeScript. `utilizando bastante em estudo` (Js já e bom, imagina superSetado!)
- C. `utilizando bastante em estudos` (Estudar algoritmos fica melhor em C)

<hr>

<div id="linguagens-utilizadas">
  Carregando...
</div>

<script>
  // Função para fazer uma requisição GET para a API do GitHub
  async function getLinguagensUtilizadas() {
    try {
      const response = await fetch("https://api.github.com/users/rianjsp/repos");
      const repositorios = await response.json();

      // Calcular as linguagens mais utilizadas
      const linguagens = {};
      repositorios.forEach(repo => {
        const { language } = repo;
        if (language) {
          linguagens[language] = (linguagens[language] || 0) + 1;
        }
      });

      // Ordenar as linguagens por quantidade de uso
      const linguagensOrdenadas = Object.entries(linguagens).sort((a, b) => b[1] - a[1]);

      // Construir HTML para exibir as linguagens
      const html = linguagensOrdenadas.map(([linguagem, quantidade]) => {
        return `<div>${linguagem}: ${quantidade}</div>`;
      }).join('');

      // Exibir as linguagens no elemento HTML
      document.getElementById("linguagens-utilizadas").innerHTML = html;
    } catch (error) {
      console.error('Erro ao obter linguagens utilizadas:', error);
      document.getElementById("linguagens-utilizadas").innerHTML = "Erro ao carregar as linguagens utilizadas.";
    }
  }

  // Chamar a função para obter e exibir as linguagens utilizadas
  getLinguagensUtilizadas();
</script>

![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=rianjsp&hide=contribs,prs)

### Contato
- 📧 Email: bigriann18@gmail.com
- 🔗 LinkedIn: [linkedin](https://www.linkedin.com/in/rian-joseph-946506239)
- 📸 Instagram: [Instagram](https://instagram.com/rian_jsp)

Feito com ❤️ por Rian Ramos 👋🏽 Entre em contato!
