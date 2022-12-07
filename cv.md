# Andrei Bernatski
### Junior Frontend Developer

---

### Contact
**Phone:** +375(29) 642-51-85<br>
**E-mail:** bernatski.a@gmail.com<br>
[LinkedIn](linkedin.com/in/iandyone)<br>

---

### Summary

**I am a novice Front-End Developer with experience building small SPA applications using JavaScript, TypeScript, React and Redux. Passionate about learning professional web development based on current technologies and modern principles of creating web applications.**

---

### Skills

- HTML5, CSS3, Sass
- JavaScript, TypeScript
- React.js, Redux, Redux Toolkit
- Git, GitHub
- VS Code, Figma

---

### Code example
Filter the array of notes by selected tags

```javascript
  function getFilteredNoteList(tags, noteList) {
        const arr = (tags.length) ? noteList.filter(note => note.noteText.split(/[\s,\n,\t,]+/).some(word => tags.includes(word))) : noteList;
        return arr.sort((a, b) => b.id - a.id);
    }
```
---

### Languages

- English \- Pre-intermediate
- Russian \- Native