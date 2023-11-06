# Hello, I'm Fabian Villagra 👋
```javascript
const description = {
    name: 'Fabián Villagra',
    country: 'Argentina',
    city: 'Formosa',
    role: 'Software Development Student (Future FullStack Developer)',
    languages: ['Spanish', 'English'],
    technologies: ['HTML', 'CSS', 'React', 'Express', 'MySQL', 'MongoDB'],
    projects: 'Currently, I am working on several projects, both personal and academic, to enhance my software development skills.',
    contacts: {
        linkedin: 'https://www.linkedin.com/in/carlos-fabián-villagra-35b1b8275/',
        email: 'fabianvillagra28@gmail.com',
    }
};

function getInfo() {
    return `
**Name:** ${description.name}
**Country:** ${description.country}
**Role:** ${description.role}
**Biography:** ${description.projects}
**Languages:** ${description.languages.join(', ')}
**Technologies:** ${description.technologies.join(', ')}
**LinkedIn:** [LinkedIn](https://www.linkedin.com/in/carlos-fabián-villagra-35b1b8275/)
**Email:** ${description.contacts.email}
`;
}

const information = getInfo();
console.log(information);
```
## Thank you for visiting my profile!
