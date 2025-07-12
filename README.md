header {
  background-color: rgba(0, 0, 0, 0.6);
  text-align: center;
  padding: 80px 20px;
  animation: flydown 2s ease-out;
}

@keyframes flydown {
  0% {
    transform: translateY(-100px);
    opacity: 0;
  }
  100% {
    transform: translateY(0px);
    opacity: 1;
  }
}

h1 {
  font-size: 3em;
  margin: 0;
  letter-spacing: 3px;
}

.content {
  background-color: rgba(0, 0, 0, 0.6);
  padding: 20px;
  line-height: 1.6;
}

iframe {
  display: block;
  margin: 20px auto;
  width: 90%;
  max-width: 720px;
  height: 400px;
  border: none;
}

footer {
  text-align: center;
  background: #111;
  padding: 15px;
  font-size: 0.9em;
}

@media (max-width: 600px) {
  h1 { font-size: 2em; }
  iframe { height: 220px; }
}
