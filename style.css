@import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap');

body {
  margin: 0;
  background-color: #000;
  color: white;
  font-family: 'Inter', sans-serif;
}

header {
  text-align: center;
  padding: 1.5rem;
  font-size: 1.5rem;
  font-weight: 700;
}

.catalog {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
  gap: 1.5rem;
  padding: 1.5rem;
}

.movie-card {
  position: relative;
  overflow: hidden;
  border-radius: 10px;
  cursor: pointer;
  transition: transform 0.3s ease;
}
.movie-card:hover {
  transform: scale(1.05);
}
.movie-card img {
  width: 100%;
  height: 300px;
  object-fit: cover;
  border-radius: 10px;
}
.movie-card .overlay {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  padding: 1rem;
  background: linear-gradient(to top, rgba(0,0,0,0.8), transparent);
}
.movie-card .overlay h2 {
  font-size: 1rem;
  margin: 0;
}

/* --- Movie Detail --- */
.movie-hero {
  position: relative;
  height: 100vh;
  overflow: hidden;
}

.movie-hero video {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  object-fit: cover;
}

.overlay-gradient {
  position: absolute;
  inset: 0;
  background: linear-gradient(to top, rgba(0,0,0,0.95) 10%, rgba(0,0,0,0.7) 50%, transparent);
}

.movie-content {
  position: relative;
  z-index: 2;
  display: flex;
  align-items: flex-end;
  height: 100%;
  padding: 2rem 4rem;
  gap: 2rem;
}

.poster {
  width: 220px;
  border-radius: 10px;
  box-shadow: 0 0 20px rgba(0,0,0,0.6);
}

.info h1 {
  font-size: 2.5rem;
  font-weight: 800;
}

.info .meta {
  color: #bbb;
  margin-top: .5rem;
}

.description {
  margin-top: 1rem;
  max-width: 700px;
  color: #ddd;
}

.actions {
  margin-top: 1.5rem;
  display: flex;
  flex-wrap: wrap;
  gap: 0.8rem;
}
.actions button {
  background-color: rgba(255,255,255,0.1);
  border: none;
  color: white;
  padding: 0.6rem 1rem;
  border-radius: 6px;
  cursor: pointer;
  transition: background-color 0.3s;
}
.actions button.play {
  background-color: white;
  color: black;
  font-weight: 600;
}
.actions button:hover {
  background-color: rgba(255,255,255,0.25);
}
button.liked, button.added {
  background-color: #e50914 !important;
}

.genres {
  margin-top: 1rem;
}
.genres span {
  background: rgba(255,255,255,0.1);
  padding: 0.3rem 0.6rem;
  border-radius: 5px;
  margin-right: 0.4rem;
  font-size: 0.8rem;
}
