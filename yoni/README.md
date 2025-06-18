yoni_app
      gap: 1rem;
      padding: 1rem;
    }

    .card {
      border: 1px solid #ccc;
      border-radius: 8px;
      padding: 1rem;
      width: 150px;
      text-align: center;
      background-color: #f9f9f9;
      cursor: pointer;
      transition: transform 0.2s;
    }

    .card:hover {
      transform: scale(1.05);
    }

    img {
      width: 100px;
      height: 100px;
      object-fit: contain;
    }
  </style>
</head>
<body>
  <h1>Pokémon Gallery</h1>
  <h2>Explore Your Favorite Pokémon!</h2>

  <button id="darkModeToggle">Toggle Dark Mode</button>
  <button id="pinkModeToggle">Toggle Pink Mode</button>
  <button id="greenModeToggle">Toggle Green Mode</button>

  <select id="filter">
    <option value="all">All</option>
    <option value="Electric">Electric</option>
    <option value="Grass">Grass</option>
    <option value="Fire">Fire</option>
    <option value="Water">Water</option>
    <option value="Psychic">Psychic</option>
    <option value="Normal">Normal</option>
    <option value="Ghost">Ghost</option>
    <option value="Dragon">Dragon</option>
  </select>

  <main class="gallery">
    <div class="card" data-type="Electric">
      <img src="assets/pikachu.png" alt="Pikachu" />
      <p>Pikachu</p>

