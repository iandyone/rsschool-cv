# Andrei Bernatski
### Junior Frontend Developer

---

### Summary

**I am a novice Front-End Developer with experience building small SPA applications using JavaScript, TypeScript, React and Redux. Passionate about learning professional web development based on current technologies and modern principles of creating web applications.**

---

### Contact
**E-mail:** bernatski.a@gmail.com<br>
**Phone:** +375(29) 642-51-85<br>
[LinkedIn](https://www.linkedin.com/in/iandyone)<br>
[GitHub](https://github.com/iandyone)<br>

---

### Skills

- HTML5, CSS3, Sass
- JavaScript, TypeScript
- React.js, Redux,
- Git, GitHub
- VS Code, Figma

---

### Languages

- English \- Pre-intermediate
- Russian \- Native

---

### Education

**Belarusian National Technical University**<br>
2015 - 2020<br>
Security System Installation, Repair, and Inspection Technology/Technician<br>
<br>

**Rolling Scopes School**<br>
2022 - current<br>
JavaScript / Front-End
<br>

---

### Projects

**Ligth Crypto**<br>
HTML, CSS, JavaScript, React, Redux, Redux-thunk, Axios, WebSocket<br>
A web tool for converting and real-time tracking cryptocurrency changes, created with JavaScript and React.js.<br>
[link](https://iandyone-light-crypto.netlify.app)<br>

**Users**<br>
HTML, CSS, JavaScript, React, Redux, Redux-thunk<br>
A web application to find GitHub users and their repositories by GitHub username.<br>
[link](https://iandyone-github-users.netlify.app)<br>

**CV**<br>
HTML, SCSS, JavaScript<br>
Andrei Bernatski - Front-End Developer CV<br>
[link](https://iandyone.github.io/CV)<br>

**Ruby Home**<br>
HTML, SCSS, JavaScript, jQuery, AOS, Font Awesome<br>
A responsive design landing page, created with CSS preprocessor and animation libraries.<br>
[link](https://iandyone.github.io/Ruby)<br>

---

### Code example
Filter the array of notes by selected tags

```javascript
  function getFilteredNoteList(tags, noteList) {
        const arr = (tags.length) ? noteList.filter(note => note.noteText.split(/[\s,\n,\t,]+/).some(word => tags.includes(word))) : noteList;
        return arr.sort((a, b) => b.id - a.id);
    }
```