/* Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  background: #f9f9f9;
  color: #333;
}

/* Navigation */
header {
  background: #222;
  padding: 1rem;
}

nav ul {
  list-style: none;
  display: flex;
  justify-content: center;
  gap: 2rem;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

/* Sections */
.section {
  padding: 2rem;
  max-width: 1000px;
  margin: auto;
}

.section h1 {
  margin-bottom: 1rem;
  text-align: center;
}

/* Card Grid */
.card-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 1.5rem;
  margin: 2rem 0;
}

.card {
  background: #fff;
  border-radius: 12px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  padding: 1rem;
  transition: transform 0.2s ease-in-out;
}

.card:hover {
  transform: translateY(-5px);
}

.card h3 {
  margin-bottom: 0.5rem;
}

a {
  color: #0073e6;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

