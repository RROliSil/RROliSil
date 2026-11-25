<div align="center">

<!-- Header Banner Animado -->
<img src="https://raw.githubusercontent.com/RROliSil/RROliSil/main/assets/header.svg" width="100%" alt="Rafael Header Banner" />

<br/><br/>

<!-- Efeito de Digitação Animado -->
<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=25D366&center=true&vCenter=true&width=640&lines=Full-Stack+Developer+(React+%2B+Node.js+%2B+TypeScript);%F0%9F%9A%80+Criador+do+Regz+App+(SaaS+Multi-Tenant+24%2F7);%F0%9F%90%B8+Criador+do+Rogue+Frog+(Android+%2F+Google+Play);%E2%98%81%EF%B8%8F+Sistemas+Cloud-Native%2C+APIs+REST+%26+Multi-Banco" alt="Typing SVG" />
</a>

<br/><br/>

[![GitHub followers](https://img.shields.io/github/followers/RROliSil?label=Followers&style=for-the-badge&color=25D366&logo=github)](https://github.com/RROliSil)
[![Regz Live](https://img.shields.io/badge/Regz_App-Online_24%2F7-6366F1?style=for-the-badge&logo=render&logoColor=white)](https://regz-app.onrender.com/Regz)
[![Google Play](https://img.shields.io/badge/Google_Play-Developer-34A853?style=for-the-badge&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.flappyfrog.game)

</div>

---

### 🚀 Projetos em Destaque *(clique em cada card para abrir a descrição detalhada)*

<br/>

<!-- ========================================================= -->
<!-- CARD 1 (DESTAQUE PRINCIPAL): REGZ APP                     -->
<!-- ========================================================= -->
<table width="100%">
  <tr>
    <td>
      <details>
        <summary>
          <table>
            <tr>
              <td width="90" align="center" valign="middle">
                <img src="https://raw.githubusercontent.com/RROliSil/regz/main/frontend/public/logo.png" width="72" alt="Regz App Logo" />
              </td>
              <td valign="middle">
                <h3>🏢 Regz App — Plataforma SaaS de Gestão de Pessoas & Portal de Colaboradores</h3>
                <p>
                  Sistema Full-Stack Multi-Tenant e Multi-Banco em produção 24/7 na nuvem (<b>React 18 • TypeScript • Node.js • Express • PostgreSQL • Docker</b>).<br/>
                  <sub><i>🔽 Clique neste card para expandir toda a arquitetura, funcionalidades de Frontend e Backend</i></sub>
                </p>
                <img src="https://img.shields.io/badge/React_18-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React 18" />
                <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
                <img src="https://img.shields.io/badge/Node.js_%2B_Express-339933?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
                <img src="https://img.shields.io/badge/PostgreSQL_SSL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
                <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
                <img src="https://img.shields.io/badge/Status-Online_24%2F7-10b981?style=flat-square" alt="Online 24/7" />
              </td>
            </tr>
          </table>
        </summary>
        <br/>
        <p>
          O <b>Regz</b> é uma plataforma corporativa completa para Gestão de Pessoas, governança de acessos e emissão de relatórios executivos — projetada de ponta a ponta com arquitetura <b>Cloud-Native 24/7</b> (Render + Supabase PostgreSQL SSL em São Paulo <code>sa-east-1</code>).
        </p>
        <h4>💻 Engenharia de Frontend (React + Vite + TypeScript)</h4>
        <ul>
          <li><b>Portal de Colaboradores:</b> CRUD com Soft Delete, validação de CPF, preenchimento automático de endereço via <b>ViaCEP</b>, geocodificação GPS (<b>OpenStreetMap Nominatim + Google Maps</b>), compressão de fotos no navegador (~25KB Base64) + Lightbox e <b>Crachá Digital com QR Code 2D</b> (download PNG e impressão).</li>
          <li><b>Validação Oficial CBO (MTE / eSocial):</b> catálogo oficial com busca por código, título ou sinônimos de mercado e normalização automática.</li>
          <li><b>Campos Dinâmicos Sem Alterar Schema (EAV):</b> criação de campos customizados (Numérico, Texto, Seleção e Sim/Não) com regras min/max e preservação de histórico.</li>
          <li><b>Relatórios & PDF Vetorial Nativo:</b> construtor livre por chips, 3 modos analíticos (Construtor, Geográfico e RBAC), modelos salvos, exportação <b>Excel CSV UTF-8 (BOM)</b> e pré-visualização de <b>PDF vetorial (<code>jsPDF</code>)</b> com alternância Retrato/Paisagem.</li>
          <li><b>UX, Acessibilidade & PWA:</b> 3 temas sincronizados (Deep Indigo, Claro e Escuro), colunas redimensionáveis persistidas em <code>localStorage</code>, Central de Acessibilidade Visual (<code>Alt + A</code>) com <b>Síntese de Voz (TTS pt-BR)</b>, Service Worker e Open Graph dinâmico.</li>
        </ul>
        <h4>⚙️ Engenharia de Backend & Multi-Banco (Node.js + Express + PostgreSQL)</h4>
        <ul>
          <li><b>50+ Endpoints REST & Segurança:</b> autenticação <b>JWT</b>, criptografia <b>bcrypt</b>, middleware granular <b>RBAC</b> (Leitura/Escrita/Sem Acesso), proteção contra força bruta (<code>HTTP 429</code> após 5 falhas) e trilha completa de <b>Logs de Auditoria</b> em <code>JSONB</code>.</li>
          <li><b>Multi-Tenancy & Roteamento Multi-Banco Online:</b> isolamento por <code>empresa_id</code>, cache dinâmico de pools por cliente (<code>getPoolForEmpresa</code>) e testador/provisionador para <b>PostgreSQL, MySQL/MariaDB, MongoDB Atlas e SQL Server</b> via Connection String (URI) com SSL/TLS automático.</li>
          <li><b>Resiliência 24/7:</b> build Docker multi-stage unificado, inicialização com retry (<code>initDbWithRetry</code>) e <code>UNNEST</code> batching em 10 tabelas relacionais.</li>
        </ul>
        <p>
          <a href="https://regz-app.onrender.com/Regz">
            <img src="https://img.shields.io/badge/Acessar_Sistema_Online-24%2F7-10b981?style=for-the-badge&logo=render&logoColor=white" alt="Acessar Online" />
          </a>
          <a href="https://github.com/RROliSil/regz">
            <img src="https://img.shields.io/badge/Ver_Repositório-RROliSil%2Fregz-6366F1?style=for-the-badge&logo=github&logoColor=white" alt="Repositório Regz" />
          </a>
          <a href="https://github.com/RROliSil/regz/blob/main/README.en.md">
            <img src="https://img.shields.io/badge/Docs-English-0EA5E9?style=for-the-badge" alt="English Docs" />
          </a>
        </p>
      </details>
    </td>
  </tr>
</table>

<br/>

<!-- ========================================================= -->
<!-- CARD 2: ROGUE FROG                                        -->
<!-- ========================================================= -->
<table width="100%">
  <tr>
    <td>
      <details>
        <summary>
          <table>
            <tr>
              <td width="130" align="center" valign="middle">
                <img src="https://raw.githubusercontent.com/RROliSil/RROliSil/main/assets/PrintBanner2.png" width="120" alt="Rogue Frog Banner" />
              </td>
              <td valign="middle">
                <h3>🐸 Rogue Frog — Roguelike Arcade Mobile (Android)</h3>
                <p>
                  Jogo arcade dinâmico publicado na Google Play Store que combina precisão clássica de desvio com progressão <b>Roguelike</b>, biomas e chefes (<b>JavaScript • HTML5 • Capacitor 7 • Android</b>).<br/>
                  <sub><i>🔽 Clique neste card para expandir as mecânicas e detalhes do jogo</i></sub>
                </p>
                <img src="https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white" alt="Android" />
                <img src="https://img.shields.io/badge/Capacitor_7-119EFF?style=flat-square&logo=capacitor&logoColor=white" alt="Capacitor 7" />
                <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
                <img src="https://img.shields.io/badge/Google_Play-Publicado-34A853?style=flat-square&logo=google-play&logoColor=white" alt="Google Play" />
              </td>
            </tr>
          </table>
        </summary>
        <br/>
        <table width="100%">
          <tr>
            <td width="58%" valign="top">
              <p>
                Um jogo arcade desafiador para Android que une a precisão clássica de desvio com mecânicas modernas de <b>Roguelike</b>, evolução de habilidades, biomas dinâmicos e batalhas épicas contra chefes!
              </p>
              <ul>
                <li>⚡ <b>Progressão Roguelike:</b> melhorias temporárias e permanentes a cada corrida.</li>
                <li>👹 <b>Batalhas de Chefes:</b> padrões de ataque únicos e desafiadores.</li>
                <li>🌍 <b>Tradução Global:</b> suporte nativo para Português, Inglês e Espanhol.</li>
                <li>🏆 <b>Integração Google Play Games:</b> placares mundiais e conquistas sincronizadas.</li>
                <li>📳 <b>Imersão Háptica:</b> resposta tátil para pulos, acertos e impactos.</li>
              </ul>
              <p>
                <a href="https://play.google.com/store/apps/details?id=com.flappyfrog.game">
                  <img src="https://img.shields.io/badge/Baixar_no-Google_Play-green?style=for-the-badge&logo=google-play&logoColor=white" alt="Play Store" />
                </a>
                <a href="https://github.com/RROliSil/rrolisil.github.io">
                  <img src="https://img.shields.io/badge/Website_Oficial-GitHub_Pages-1E293B?style=for-the-badge&logo=github&logoColor=white" alt="Site Oficial" />
                </a>
              </p>
            </td>
            <td width="42%" align="center" valign="middle">
              <a href="https://play.google.com/store/apps/details?id=com.flappyfrog.game">
                <img src="https://raw.githubusercontent.com/RROliSil/RROliSil/main/assets/PrintBanner2.png" width="100%" alt="Rogue Frog Screenshot" />
              </a>
            </td>
          </tr>
        </table>
      </details>
    </td>
  </tr>
</table>

---

### 💻 Minha Tech Stack & Ferramentas

<div align="center">

| Categoria | Tecnologias |
| :--- | :--- |
| **Frontend & Web** | ![React](https://img.shields.io/badge/React_18-61DAFB?style=for-the-badge&logo=react&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white) |
| **Backend & Bancos** | ![NodeJS](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white) ![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white) |
| **Cloud & DevOps** | ![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=black) ![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=for-the-badge&logo=supabase&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white) |
| **Mobile & Publicação** | ![Android](https://img.shields.io/badge/Android-3DDC84?style=for-the-badge&logo=android&logoColor=white) ![Capacitor](https://img.shields.io/badge/Capacitor_7-119EFF?style=for-the-badge&logo=capacitor&logoColor=white) ![Gradle](https://img.shields.io/badge/Gradle-02303A?style=for-the-badge&logo=gradle&logoColor=white) ![Google Play Console](https://img.shields.io/badge/Play_Console-414141?style=for-the-badge&logo=google-play&logoColor=white) ![AdMob](https://img.shields.io/badge/Google_AdMob-EA4335?style=for-the-badge&logo=google-admob&logoColor=white) |

</div>

---

### 📊 Estatísticas do GitHub

<div align="center">
  <img height="175em" src="https://github-stats-extended.vercel.app/api?username=RROliSil&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&bg_color=0D1117" alt="GitHub Stats" />
  <img height="175em" src="https://github-readme-streak-stats.herokuapp.com/?user=RROliSil&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" />
</div>

<div align="center" style="margin-top: 10px;">
  <img height="165em" src="https://github-stats-extended.vercel.app/api/top-langs/?username=RROliSil&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" />
</div>

---

<div align="center">

<!-- Footer Wave Animado -->
<img src="https://raw.githubusercontent.com/RROliSil/RROliSil/main/assets/footer.svg" width="100%" alt="Footer Wave" />

<p><i>"Grandes sistemas e grandes jogos nascem da mesma disciplina: um salto bem construído de cada vez." 🚀🐸</i></p>

</div>
