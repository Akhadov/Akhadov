### Hi there, I'm Shakhriyor Akhadov! 👋 

[![LinkedIn URL](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin&style=for-the-badge)](https://shorturl.at/eDFMS)

## **I'm a Software Engineer.**

- 🎯 **I’m currently learning**: - software architecture and design principles.
- 💬 **Ask me about**: .NET, ASP.NET, RESTful APIs, PostgreSQL
- 📫 **How to reach me**: Reach out via shakhriyor.akhadov@gmail.com or connect with me on LinkedIn! 👆

<hr/>

![GitHub stats](https://github-readme-stats.vercel.app/api?username=akhadov&count_private=true&show_icons=true&hide=stars)


<div id="github-stats"></div>

<script>
    fetch('https://api.github.com/users/akhadov/repos')
    .then(response => response.json())
    .then(data => {
        const totalCommits = data.reduce((acc, repo) => acc + repo.stargazers_count, 0);
        document.getElementById('github-stats').innerHTML = `
            <img src="https://github-readme-stats.vercel.app/api?username=akhadov&count_private=true&show_icons=true&hide=stars&custom_title=GitHub%20Stats%20${new Date().getFullYear()}&theme=dark" alt="GitHub stats" />
            <p>Total commits in ${new Date().getFullYear()}: ${totalCommits}</p>
        `;
    })
    .catch(error => console.error('Error fetching GitHub stats:', error));
</script>

---
💻 Main Tech Stack

<img src="https://github.com/devicons/devicon/blob/master/icons/dotnetcore/dotnetcore-original.svg" alt="dotnet logo" width="40" height="40" /> <img src="https://github.com/devicons/devicon/blob/master/icons/csharp/csharp-original.svg" alt="csharp logo" width="40" height="40" /> <img src="https://github.com/devicons/devicon/blob/master/icons/docker/docker-plain-wordmark.svg" alt="csharp logo" width="40" height="40" /> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/>

---
