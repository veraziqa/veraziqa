## Hi there 👋

<!--
**veraziqa/veraziqa** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Veraziqa</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <!-- Header Section -->
    <header>
        <div class="header-content">
            <h1>Selamat Datang di Veraziqa</h1>
            <p>Im Vera, 18 years old, still don't know what to do with 2025</p>
        </div>
    </header>
    body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f5;
    margin: 0;
    padding: 0;
    color: #333;
}

header {
    background-color: #8a2be2;
    color: white;
    text-align: center;
    padding: 20px 0;
}

h1 {
    margin: 0;
}

main {
    padding: 20px;
}

.gallery {
    text-align: center;
}

.photo-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 10px;
}

.photo-grid img {
    width: 100%;
    border-radius: 10px;
    transition: transform 0.5s;
}

.photo-grid img:hover {
    transform: scale(1.1);
}

/* Animasi untuk header */
header {
    animation: fadeIn 2s ease-in-out;
}

@keyframes fadeIn {
    from {
        opacity: 0;
    }
    to {
        opacity: 1;
    }
}
// scripts.js

// Placeholder for any future JavaScript animations or interactions

document.addEventListener('DOMContentLoaded', () => {
    console.log('Document is fully loaded and parsed.');
    // Add any JavaScript animations or interactions here
});
